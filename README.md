**PLEASE NOTE**: For reasons that are unclear to me, jekyllxhbit pages don't appear to render correctly when hosted as github pages. You can see this by comparing [colaborativa.github.io/jekyllxhibit](colaborativa.github.io/jekyllxhibit) and [http://jekyllxhibit.colaborativa.eu](http://jekyllxhibit.colaborativa.eu). This fork doesn't provide a fix for this issue, though it may do so in the future.

# *Jekyllxhibit* Template Tutorial: Creaing web pages for collaborativa.eu
Last updated: April 22, 2013

## 1. Domain registration (optional)

The first step is to register a .EU domain or .COM. If you haven't registered a domain our website will be hosted on a [GitHub][6] subdomain.

> http://USERNAME.github.io

## 2. Register on [GitHub][6]

We will use the following three tools to create your website:

* [Jekyll](http://jekyllrb.com) is a simple static HTML webpage generator.
* [Prose.io](http://prose.io) is an editor for content in Jekyll format.
* [GitHub Pages](http://pages.github.com) provides free hosting for pages generated using Jekyll.

Registering on [GitHub][6] can be done on the site's homepage - it's easy and free!

<a href="http://www.flickr.com/photos/50381188@N06/8637580247/" title="Paso-02-GitHub por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8244/8637580247_991f7df110.jpg" width="500" height="286" alt="Paso-02-GitHub"></a>

## 3. Copy the *Jekyllxhibit* template into your [GitHub][6] accoint

Go to Colaborativa's account on [GitHub][6] and find the *Jekyllxhibit* repository:

> [https://github.com/colaborativa/jekyllxhibit][7]

 <a href="http://www.flickr.com/photos/50381188@N06/8638707576/" title="Paso-03-01-GitHub-Clonar por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8399/8638707576_0138553b93.jpg" width="500" height="286" alt="Paso-03-01-GitHub-Clonar"></a>

Click on the **FORK this repo** icon on the top right to copy the current version of the template to your account.


## 4. Rename the template

There's one final step before you can start adding content. You may need to rename the current version of the template:

* If you're going to use the template for a *profile* page and you have no control over the domain or you're going to use your own domain then you have to use this nomenclature:

> USERNAME.github.io

* If you're going to use the template for a *project* page and you're going to use a subdomain within your main domain then the name you choose for the template is unimportant.

You should be able to access the website at this URL:

> http://username.github.io

To rename the template, click on the repository's **Settings** tab. Enter the new name and then click **Rename**. Now, make sure that the GitHub Pages Settings section is activated and reads:

> Your site is published at http://www.username.github.io

<a href="http://www.flickr.com/photos/50381188@N06/8638715922/" title="Paso-03-01-GitHub-Renombrar por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8118/8638715922_8ba3f8b6d4.jpg" width="500" height="286" alt="Paso-03-01-GitHub-Renombrar"></a>

## 5. Configure the [GitHub][6] template.

The `CNAME` file in the *Jekyllxhibit* template must be edited.

* If you're going to use your own domain, the `CNAME` file must include its name (for example, `collaborativa.eu`). We'll have to wait about ten minutes to see the updated domain.

* If you don't have your own domain, the website will be at `USERNAME.github.io`, and the `CNAME` file should contain a blank line.

To edit the `CNAME` file, go to your copy of the template on [GitHub][6] and look at the files contained.

Para editar el archivo `CNAME` ir a nuestra plantilla en [GitHub][6], veremos entonces la lista de archivos que la forman. Click on the `CNAME` file and you'll see:

<a href="http://www.flickr.com/photos/50381188@N06/8637668359/" title="Paso-05-01-GitHub-Editar-CNAME por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8528/8637668359_e91c19c5f9.jpg" width="500" height="286" alt="Paso-05-01-GitHub-Editar-CNAME"></a>

Next click **Edit**, edit the file as needed and click the **Commit Changes** button on the bottom right.

<a href="http://www.flickr.com/photos/50381188@N06/8637673623/" title="Paso-05-02-GitHub-Editar-CNAME por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8114/8637673623_7e97737735.jpg" width="500" height="325" alt="Paso-05-02-GitHub-Editar-CNAME"></a>

Now, go to username.github.com in your browser of choice - you should see the website. Now you can start adding content!


## 6. Description of the template structure on [GitHub][6]

* The `_config.yml` file: Configuration information for the template
* The `_layouts` directory: HTML templates that will be used to display posts if weo only have a call to `default.html`.
* The `_posts` directory: Your website's content is located in this directory. FIles should be formatted using Markdown and should be named using **YYYY-MM-DD-title.md** as their format. They'll be displayed in order by date. This directory contains two subdirectories:
  * The `sections` directory: Contains the sections listed on the left bar. Each section is associated with a number of exhibits.
  * The `exhibits` directory: Contains your projects, articles, news, etc. Each exhibit is associated with a particular section.

* The `stylesheets` directory: CSS stylesheets for the site.

## 7. Add Content Using [Prose.io][4]

To begin adding content, go to:

> [http://prose.io][4]

and authorize your [GitHub][6] credentials by clicking **Authorize with GitHub**.

<a href="http://www.flickr.com/photos/50381188@N06/8638725787/" title="Paso-07-01-Proseio-Acceder por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8522/8638725787_9a2ec88a12.jpg" width="500" height="271" alt="Paso-07-01-Proseio-Acceder"></a>

[Prose.io][4] tendrá acceso a nuestra plantilla alojada en [GitHub][6] y nos permitirá añadir contenidos. [Prose.io][4] nos mostrará una lista de proyectos alojados en [GitHub][6], hacemos click en la plantilla que deseamos modificar y aparecerá la siguiente pantalla:

<a href="http://www.flickr.com/photos/50381188@N06/8638736133/" title="Paso-07-02-Proseio-Listado por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8525/8638736133_9c982f554d.jpg" width="500" height="271" alt="Paso-07-02-Proseio-Listado"></a>


You can add or modify content in the `exhibits` directory (containing our projects, articles, news, etc.)  and the `sections` directory containing sections into which the exhibits are classified. The list of sections will be shown in the column on the left.

### 7.1 Edit Sections Using [Prose.io][4]

To edit an existing section click on the `sections` directory to display the existing sections:

<a href="http://www.flickr.com/photos/50381188@N06/8638754333/" title="Paso-07-03-Proseio-sections por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8119/8638754333_d91cef9fbd.jpg" width="500" height="271" alt="Paso-07-03-Proseio-sections"></a>

Click on the exhibit you want to edit and it will open for modification:

<a href="http://www.flickr.com/photos/50381188@N06/8638754525/" title="Paso-07-04-Proseio-sections-editar por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8532/8638754525_30afa7ff88.jpg" width="500" height="271" alt="Paso-07-04-Proseio-sections-editar"></a>

Now, we'll review the options you have for editing the data.

#### *Markdown* Format

All files are written in *Markdown* format. It's a simple markup language that can incorporate HTML for more detailed control.

El formato *Markdown* genera archivos muy limpios y separa estilo de contenido, esto es positivo ya que puedes reutilizar el mismo contenido con distintos formatos. Markdown generates clean, minimal files. They can be relatively easily reused between exhibits.

We recommend this editor for viewing, editing, and proofreading text:

> [http://jrmoran.com/playground/markdown-live-editor/][5]

If you click the **M** button on the editing bar, you'll display a simple tutorial on Markdown syntax:

<a href="http://www.flickr.com/photos/50381188@N06/8638769529/" title="Paso-07-05-Proseio-barra-edicion-markdown por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8106/8638769529_8a0f461062.jpg" width="500" height="396" alt="Paso-07-05-Proseio-barra-edicion-markdown"></a>

#### Metadata Header

All of the files have a header containing several configuration variables. Text and other exhibit content follows this metadata. By using the **Metadata** button you can show or hide this extra data.

<a href="http://www.flickr.com/photos/50381188@N06/8639873168/" title="Paso-07-06-Proseio-barra-edicion-metadata por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8539/8639873168_62718f54f7.jpg" width="500" height="396" alt="Paso-07-06-Proseio-barra-edicion-metadata"></a>

Files in the `sections` directory only contain metadata - they should have data in the **title** section (which will be displayed on the side), and nothing else.

#### Published Sections

Another option in the edit bar allows us to indicate whether or not the section will be published on your website. It's represented by the **Tools** icon. This option is useful when creating new sections that haven't been populated with content.

<a href="http://www.flickr.com/photos/50381188@N06/8639873292/" title="Paso-07-07-Proseio-barra-edicion-publicado por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8521/8639873292_08de43dce8.jpg" width="500" height="396" alt="Paso-07-07-Proseio-barra-edicion-publicado"></a>

#### Preview

By clicking the **Preview** button, represented by an eye icon, you'll see how your section or exhibit will be displayed on the website. Because sections only contain title data, the preview will show a blank screen.

<a href="http://www.flickr.com/photos/50381188@N06/8638769937/" title="Paso-07-08-Proseio-barra-edicion-vistapreliminar por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8255/8638769937_22b9321aea.jpg" width="500" height="396" alt="Paso-07-08-Proseio-barra-edicion-vistapreliminar"></a>

#### Save and Exit

To save your changes, click on the **Save** button in the edit toolbar and on the following screen:

<a href="http://www.flickr.com/photos/50381188@N06/8639903062/" title="Paso-07-09-Proseio-barra-edicion-guardarysalir por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8384/8639903062_6c85fab690.jpg" width="500" height="396" alt="Paso-07-09-Proseio-barra-edicion-guardarysalir"></a>

Click on the **Commit** button to confirm the changes. Each time you make a change it's recorded along with a customizable message.

### 7.2 Add Photos Using [Prose][4] and [Flickr][9]

To add pictures to one of the files in `exhibits`, first select the file using [Prose][4] and enter the editing screen.

<a href="http://www.flickr.com/photos/50381188@N06/8639973616/" title="Paso-07-10-Proseio-flickr por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8542/8639973616_c271f67bb5.jpg" width="500" height="396" alt="Paso-07-10-Proseio-flickr"></a>

One easy way to store your website's images is by using [Flickr's][9] free hosting service. To do so, you must register with [Flickr][9] and then add photos to the account. (This is beyond this tutorial's scope.) To insert a photo into one of our exhibits, just click the **Share** button, copy the HTML code associated with the image, and paste it into the exhibit file.

<a href="http://www.flickr.com/photos/50381188@N06/8639974016/" title="Paso-07-11-Proseio-flickr por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8117/8639974016_c2a77b12fa.jpg" width="500" height="289" alt="Paso-07-11-Proseio-flickr"></a>

In the following screenshot we can see the image inserted in our exhibit.

<a href="http://www.flickr.com/photos/50381188@N06/8638875757/" title="Paso-07-13-Proseio-flickr por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8100/8638875757_867e85aa81.jpg" width="500" height="396" alt="Paso-07-13-Proseio-flickr"></a>

In the below screenshot, we can see a preview of how the image would display on your website.

<a href="http://www.flickr.com/photos/50381188@N06/8638875923/" title="Paso-07-14-Proseio-flickr por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8111/8638875923_b088d5a880.jpg" width="500" height="396" alt="Paso-07-14-Proseio-flickr"></a>

After finishing editing, click **Save** and then **Commit** to make your changes, as described above.

<a href="http://www.flickr.com/photos/50381188@N06/8638878691/" title="Paso-07-15-Proseio-flickr por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8259/8638878691_d4e66bf223.jpg" width="500" height="396" alt="Paso-07-15-Proseio-flickr"></a>

### 7.3 Add Videos Using [Prose][4] and [Vimeo][8]

To add videos to the files in `exhibits`, use a similar process. We recommend using the free hosting service provided by [Vimeo][8]. The first step is registering, using the form shown in this screenshot:

<a href="http://www.flickr.com/photos/50381188@N06/8640024066/" title="Paso-07-16-Proseio-vimeo por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8099/8640024066_a1b65e15a3.jpg" width="500" height="396" alt="Paso-07-16-Proseio-vimeo"></a>

Next, go to [Vimeo][8] and upload your first video. To insert a video into one of our exhibits, just click the **Share** button at the top right corner of the video, copy the HTML beneath the word **Embed**.

<a href="http://www.flickr.com/photos/50381188@N06/8639974276/" title="Paso-07-12-Proseio-vimeo por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8522/8639974276_c5b2b83e89.jpg" width="500" height="289" alt="Paso-07-12-Proseio-vimeo"></a>

Paste the text into the exhibit file.

<a href="http://www.flickr.com/photos/50381188@N06/8640024222/" title="Paso-07-17-Proseio-vimeo por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8108/8640024222_2c4ee838f7.jpg" width="500" height="396" alt="Paso-07-17-Proseio-vimeo"></a>

Before saving the exhibit file with the inserted text, you'll need to make a few changes. As of the writing (of the original version) of this tutorial, Jekyll doesn't understand variables that haven't been assigned a value. In the example below, **webkitAllowFullScreen**, **mozallowfullscreen** and **allowFullScreen** would be misinterpreted.

```<iframe src="http://player.vimeo.com/video/58116607" width="500" height="281" frameborder="0" webkitAllowFullScreen mozallowfullscreen
 allowFullScreen> </iframe> <p><a href="http://vimeo.com/58116607">Montaje RepRapPro Huxley en Colaboratorio</a> from <a href="http://vimeo.com/colaborativa">colaborativa</a> on <a
 href="http://vimeo.com">Vimeo</a>.</p>```

To fix the above text, edit it as follows:

```<iframe
 src="http://player.vimeo.com/video/58116607"  width="500" height="281" frameborder="0"> </iframe> <p><a href="http://vimeo.com/58116607">Montaje RepRapPro Huxley en Colaboratorio</a>
 from <a href="http://vimeo.com/colaborativa">colaborativa</a>
 on <a href="http://vimeo.com">Vimeo</a>.</p>```

If you click the **Preview** button, you'll see that after editing the video is now correctly inserted into the exhibit.

<a href="http://www.flickr.com/photos/50381188@N06/8638920807/" title="Paso-07-18-Proseio-vimeo por colaborativa.eu, en Flickr"><img src="http://farm9.staticflickr.com/8104/8638920807_5a5ef1c6eb.jpg" width="500" height="396" alt="Paso-07-18-Proseio-vimeo"></a>

## Credits

The *Jekyllxhibit* template is an open source project distributed under the [licencia MIT][1]. The text and images are distributed under a creative commons license [CC BY 3.0 ES][2].

## Contact Information

You can contact us for more information at info@colaborativa.eu  or by visiting our website at [colaborativa.eu][3].

[1]: http://opensource.org/licenses/MIT
[2]: http://creativecommons.org/licenses/by/3.0/es/
[3]: http://colaborativa.eu
[4]: http://prose.io
[5]: http://jrmoran.com/playground/markdown-live-editor/
[6]: http://github.com
[7]: https://github.com/colaborativa/jekyllxhibit
[8]: http://vimeo.com
[9]: http://flickr.com
