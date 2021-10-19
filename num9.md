# WRRC and Java

## High-level HTTP 

### Local Processing

First the browser needs to translate the address to an IP address if it does not already know it. If it knows it, nothing happens at this point. If it does not know it, it contacts a DNS server to resolve the name.

Java example : 

>URL url = new URL("http://example.com");
HttpURLConnection con = (HttpURLConnection) url.openConnection();
con.setRequestMethod("GET");

### Resolve an IP

bypass CDN and proxy layers when requesting content from the site by sending those web requests directly to a specific IP address without using the site's public DNS records.

Java example : 

>Map<String, String> parameters = new HashMap<>();
parameters.put("param1", "val");

con.setDoOutput(true);
DataOutputStream out = new DataOutputStream(con.getOutputStream());
out.writeBytes(ParameterStringBuilder.getParamsString(parameters));
out.flush();
out.close();


### Establish a TCP Connection

Then browser will open a TCP connection to the IP address of the entered address and send a HTTP GET request over.

>BufferedReader in = new BufferedReader(
  new InputStreamReader(con.getInputStream()));
String inputLine;
StringBuffer content = new StringBuffer();
while ((inputLine = in.readLine()) != null) {
    content.append(inputLine);
}
in.close();

### Send an HTTP Request

The server software will get this HTTP request. It will somehow generate a HTTP response and send that back trough the TCP connection. How the server does this is server software dependent. which then generates the response sent to the browser. When the response is sent, in HTTP version 1.0 the connection is closed. HTTP 1.1 can have persistent connections though.

>public class FullResponseBuilder {
    public static String getFullResponse(HttpURLConnection con) throws IOException {
        StringBuilder fullResponseBuilder = new StringBuilder();

        // read status and message

        // read headers

        // read response content

        return fullResponseBuilder.toString();
    }
}


### Tearing Down and Cleaning Up

The browser begins processing what it has received. If it is an image, data, or other media file that is being consumed by some application inside the browser, a variety of things can happen.


The example are from "Do a Simple HTTP Request in Java" ["Do a Simple HTTP Request in Java"](https://www.baeldung.com/java-http-request)


<hr>
&nbsp;
&nbsp;

Get back to [EMAM'S HOMEPAGE](https://emam96.github.io/reading-notes/)

 I have created this page as a part of my project using Github, Please visit my [profile](https://github.com/Emam96), I will be more than happy to hear from you all.      &nbsp;        &nbsp;       &nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      © Emam Shararah 2021