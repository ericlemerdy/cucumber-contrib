cucumber-contrib
================

Sample
------

See `/src/test/java/sample/coffeemachine/RunCucumberTest`


Usage
-----

1. Using the pdf formatter

Decorate your Cucumber test with:

    @RunWith(Cucumber.class)  
    @Cucumber.Options(  
        format = {"cucumber.contrib.formatter.pdf.PdfFormatter"}  
    )  
    public class MyCucumberTest {


2. Adding a front page

    @RunWith(Cucumber.class)  
    @Cucumber.Options(
