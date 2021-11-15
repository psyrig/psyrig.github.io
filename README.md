# [Psy-Rig-Hands](https://psyrig.github.io/)

## Configuration 

Settings that affect your entire site can be changed in **'_confing.yml.'**

Some useful settings are explained below. For further information: [Click here](https://mmistakes.github.io/minimal-mistakes/docs/configuration/#theme)

### Skins
Change the color scheme of the theme using one of the provided 'minimal_mistakes_skins'

### Default Site Settings 

|Setting                          | Explanation                                                                                                                       |
|---------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|
|'title'                          | name of your site                                                                                                                 | 
|'subtitle'                       | short tagline that appears below the title in site masthead                                                                       |
|'name'                           | used to assign a site author                                                                                                      |
|#SEO; #Social Sharing; #Analytics| optional, but good idea to improve SEO and links shared from the site                                                             |
|#Site Author                     | defining what appears in the author sidebar (multiple authors -> values can be overridden with custom YAML Front Matter/data file)|
|'footer'                         | e.g. social media links                                                                                                           | 
|'defaults'                       | front matter defaults for posts, pages & collections                                                                              |


---
## Pages/Posts

Add .md files to /_pages/.

### YAML Front Matter

|Setting          | Command                                                           |
|-----------------|-------------------------------------------------------------------|
|post dates       | show_date: true/false (or apply as a default in _'_confing.yml'_ )| 
|reading time     | read_time: true/false ("-"                                        |
|author           | author_profile: true/false                                        |
|site nav box     | toc:true/false                                                    |

### HTML Tags and Formatting

A variety of common markup showing how the theme styles them: [Click here](https://mmistakes.github.io/minimal-mistakes/markup/markup-html-tags-and-formatting/)

### Images

Add images to /asstets/images/.

|Image            | Size                   |
|-----------------|------------------------|
|logo             | e.g. 96x96, 500x500    |
|avatar/bio photo | from 200x200           |
|header banner    | from 1600x586          |
|project teaser   | 600x400                |
|project banner   | from 1200x400          |
|project normal   | 700x362                |
|item normal      | 300x200                |

More image demos: 
- [Standard](https://mmistakes.github.io/minimal-mistakes/post%20formats/post-image-standard/)
- [Gallery](https://mmistakes.github.io/minimal-mistakes/markup-more-images/)
- [Alignment](https://mmistakes.github.io/minimal-mistakes/markup/markup-image-alignment/)

### Links to PDF 

Add .pdf files to /assets/pdf/.

<a href="/assets/pdf/test_file.pdf">[&rarr; PDF link example]</a>






