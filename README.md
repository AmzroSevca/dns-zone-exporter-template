# DNS Zone Exporter Template
This is a simple HTML table template built for selecting HTML table elements within DNS record pages using DevTools and dumping the contents into a local file for safekeeping and reference. Please keep in mind that this is just a template and not an automated process. You must find and select the HTMl tables yourself within the DNS Zone / DNS records page of your domain registrar. This is just an easy way to keep that information organized in a neat manner since not all registrars offer the feature of exporting DNS records as a document.

## Getting the Time and Date

To get the time and date for whenever you exported the DNS Record simply use the `td-get` url file which will take you to [https://www.pastetime.com/now/utc](https://www.pastetime.com/now/utc) where you can copy a time and date stamp to include in your index file.

## Creating Multiple Exports

If you want to create multiple DNS record exports that belong to different domain registrars or are associated with different projects and organizations, simply duplicate index and rename it to something else. If you want to simply export multiple DNS records for a list of domains that a single entity owns with a single registrar then you do not need to duplicate the index file.

## "This is a very manual solution..."

Yes, I am aware that this is a very manual solution. This should only be used in the event that your domain registrar does not natively support the exporting of DNS records. Automating this process would involve writing Python scripts, messing around with APIs of a dozen registrars, and trying to make sure secret variables are stored properly. If you want to build something more automated though as a container for Docker, that would be pretty cool and I'll be cheering you on! :)
