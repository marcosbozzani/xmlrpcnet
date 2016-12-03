
What is XML-RPC?
----------------

To quote the XML-RPC.com site:

> It's a spec and a set of implementations that allow software running on disparate operating systems, running in different environments to make procedure calls over the Internet. It's remote procedure calling using HTTP as the transport and XML as the encoding. XML-RPC is designed to be as simple as possible, while allowing complex data structures to be transmitted, processed and returned."  

What is XML-RPC.NET?
--------------------

XML-RPC.NET is a .NET class library for implementing XML-RPC clients and servers, created by Charles Cook (https://github.com/charlescook)

Nuget
-----

**Client**: https://www.nuget.org/packages/xmlrpcnet/3.0.0.266

**Server**: https://www.nuget.org/packages/xmlrpcnet-server/3.0.0.266

Documentation
-------------
http://xml-rpc.net/faq/xmlrpcnetfaq-3-0-0.html

Features 
--------
 - Interface based definition of XML-RPC servers and clients
 - Code generation of type-safe client proxies
 - Silverlight and Windows Phone 7
 - ASP.NET Web Services which support both XML-RPC and SOAP
 - Client support for asynchronous calls
 - Client support for various XML encodings and XML indentation styles (some other XML-RPC server implementations only accept certain indentation styles)
 - Built-in support for XML-RPC Introspection API on server
 - Dynamic generation of documentation page at URL of XML-RPC end-point
 - Support for mapping XML-RPC method and struct member names to .NET-compatible names
 - Support for Unicode XML-RPC strings in both client and server
 - Support for optional struct members when mapping between .NET and XML-RPC types
 - &lt;i8&gt; XML-RPC extension
 - &lt;nil&gt; XML-RPC extension
 - Support for .NET Remoting on both client and server
 
Prequisites
-----------
Assemblies CookComputing.XmlRpcV2.dll and CookComputing.XmlRpcServerV2.dll 
require 2.0 .NET runtime and run on all later versions.

Assembly CookComputing.XmlRpcSilverlight.dll requires Silverlight 4 runtime.
 
Misc
----
**Website**: http://xml-rpc.net/

**Version**: xml-rpc.net.3.0.0.266

**Original source**: https://code.google.com/archive/p/xmlrpcnet/downloads