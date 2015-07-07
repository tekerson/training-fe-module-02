# Backbase Training Exercise

## Portal Frontend - Module 2

### Exercise 1, part a

_note: This exercise is 1 of 4 in a series of exercises that follow on from each other and should not be used independently_
_note: All exercises use the [standard portal set-up for backbase trainings](https://my.backbase.com/resources/how-to-guides/getting-your-first-launchpad-based-portal-set-up/)_

#### Description

In this exercise, you will learn how to use `g:include` to retrieve and transform content from a remote RSS feed, and display it in your widget.

#### Steps

 - Create a new widget named **Feed Reader**, based on the Widget Development Methodology
 - Let the widget include the content of an RSS feed using **g:include**
 - Use provided **Camel route** to transform xml to html

#### Additional resources

 - [Camel configuration](../../../../../../../../feed-service-module/src/main/resources/META-INF/spring/backbase-integration-service.xml#L24-L35)
 - [RSS xsl](../../../../../../../../feed-service-module/src/main/resources/xslt/rss/rss2xhtml.xsl)
 - [catalog-pf2e1a-feed-reader-widget.xml](catalog-pf2e1a-feed-reader-widget.xml)

#### References

 - [Widget Development Methodology](https://github.com/Backbase/methodology-widget-development)
 - [g:include Reference](https://my.backbase.com/resources/documentation/portal/5.5.1.0/refc_gnam_include.html)
 - [Mustache](https://mustache.github.io/mustache.5.html)