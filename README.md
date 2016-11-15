# Current D8 status of the top 50 Drupal modules<sup>[1](#note1)</sup>

|Module|D8 Status|D7 Usage<sup>[2](#note2)</sup>|D8 Usage|Notes|
| ------ | ------ | ------ | ------ | ------ |
|Chaos tool suite (ctools)|Alpha|88%|25%||
|Views|Core|83%|NA||
|Token|Beta|75%|26%||
|Libraries API|Dev|69%|6%|Only needed for external libs in D8|
|Pathauto|Beta|65%|21%||
|Entity API|Alpha|61%|9%|Many D7 features are in D8 core|
|Administration menu|GA|49%|21%|Functionality in admin_toolbar in D8|
|Webform|Beta|47%|NA|Functionality split.<sup>[3](#note3)</sup>|
|jQuery Update|Core|49%|NA||
|Date|Core|45%|NA|Partially in core|
|IMCE|GA|42%|5%|Largely unneeded in D8|
|CKEditor - WYSIWYG HTML editor|Core|40%|NA||
|Google Analytics|GA|35%|9%||
|Link|Core|34%|NA||
|Wysiwyg|Core|33%|NA||
|Module Filter|Dev|33%|0%|Core has some functionality|
|Metatag|Beta|32%|12%||
|Rules|Alpha|29%|2%||
|Entity Reference|Core|28%|NA||
|Features|GA|29%|5%||
|Backup and Migrate|Alpha|28%|3%||
|Media|NA|28%|NA|Functionality split.<sup>[4](#note4)</sup>|
|XML Sitemap|Alpha|27%|2%||
|Colorbox|GA|27%|5%||
|Field Group|RC|26%|11%||
|Views Bulk Operations (VBO)|Dev|25%|0%||
|Views Slideshow|GA|25%|5%||
|Transliteration|Core|26%|NA||
|Variable|Dev|24%|NA|Largely unneeded in D8|
|CAPTCHA|Alpha|23%|5%||
|Panels|Beta|23%|4%||
|Localization update|Core|22%|NA||
|Menu block|GA|21%|2%||
|Devel|Alpha|21%|12%||
|Context|Alpha|20%|1%||
|Internationalization|Core|19%|NA||
|Global Redirect|NA|18%|NA|Functionality in D8 redirect module|
|Redirect|Alpha|18%|6%||
|IMCE Wysiwyg bridge|NA|16%|NA|Not relevant in D8|
|Strongarm|NA|16%|NA|Not relevant in D8|
|Field collection|Alpha|16%|5%||
|File Entity (fieldable files)|Beta|15%|2%|Other options in D8|
|Display Suite|GA|15%|6%||
|Menu attributes|Dev|15%|0%||
|Block Class|Alpha|15%|2%||
|Email Field|Core|14%|NA||
|Superfish|RC|14%|3%||
|Address Field|RC|14%|3%|Functionality in D8 address module|
|References|Core|12%|NA||
|Job Scheduler|Dev|13%|0%||


|SUMMARY|||
| ------ | ------:| ------:| 
|In core|12|24%|
|GA|8|16%|
|RC|3|6%|
|Beta|6|12%|
|Alpha|11|22%|
|Dev|6|12%|
|NA|4|8%|

<a name="note1"><strong>Note1:</strong></a> "Top" 50 modules are the 50 most installed D7 modules according to [the _Download & Extend_ page on D.O][top50].

<a name="note2"><strong>Note2:</strong></a> Usage statistics -- including core -- scraped from
`drupal.org/project/usage/{PROJECT}`. Usage Percentages are the number of sites that report using that module divided by the
total number of sites that report using D7 or D8.

<a name="note3"><strong>Note3:</strong></a> Previous use cases for Webform are largely covered 
by the Contact module (core) and Contact Storage module (contrib - Beta). Use
cases _not_ covered by those modules, that is, forms as content, are generally
convered by the YAML Form module (contrib - beta). There is an issue to change
YAML Form's name to Webform.

<a name="note4"><strong>Note4:</strong></a> Functionality provided by D7 Media module has been
expanded and split into several submodules. Notably:

* Entity Browser (Alpha)
* Entity Embed (Beta)
* Media Entity (GA)


[top50]: https://www.drupal.org/project/project_module?f%5B0%5D=&f%5B1%5D=&f%5B2%5D=&f%5B3%5D=drupal_core%3A103&f%5B4%5D=sm_field_project_type%3Afull&text=&solrsort=iss_project_release_usage+desc&op=Search)