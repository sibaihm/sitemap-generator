# sitemap-generator

Generate a site map

## What can the sitemap-generator do?

It returns all the found URLs of a given web site.

## How to use it?

* Clone the repository
* Import the package to your project
* Create a SitemapGenerator object passing the wanted URL
```java
SitemapGenerator sitemap = new SitemapGenerator("http://your-web-site.com");
```
* Invoke the create method, it returns a string set
```java
sitemap.create();
```
* You can print the results on the console by
```java
sitemap.print();
```
* You can save the found URLs into a TXT file on desktop
```java
sitemap.saveToFile();
```

## TODO

* Support URL query string
* Export to XML
* Specify the depth
