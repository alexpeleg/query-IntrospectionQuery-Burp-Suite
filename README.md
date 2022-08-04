# query-IntrospectionQuery-Burp-Suite
IntrospectionQuery for Burp Suite allows you to extract the schema from GraphQL

Once I was doing a penetration test on a GraphQL based application, I needed a way to identify the schema and queries. 
There is a great way to do so, using IntrospectionQuery.

Once searching online, no good payloads were identified to inject into my Burp Suite Repeater session. 

After getting the response, you can use a great tool called GraphQL Voyager by Ivan Goncharov. and load the schema to it. 

