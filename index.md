---
layout: default
title: Dropzone.js
---

<section markdown="1">

Try it out!
===========

<div id="dropzone"><form action="/upload" class="dropzone needsclick" id="demo-upload">

  <div class="dz-message needsclick">
    <button type="button" class="dz-button">Drop files here or click to upload.</button><br>
    <span class="note needsclick">(This is just a demo dropzone. Selected files are <strong>not</strong> actually uploaded.)</span>
  </div>

</form></div>

</section>



<section class="news" markdown="1">

News
====

{% comment %}
{% include _for_hire.html %}
{% endcomment %}

**Dropzone 5.7.2, July 23rd 2020**

Lots of minor fixes in this small release. Please check the CHANGELOG to see
a summary of the changes.

I know that most of you are unhappy that I can't fix all bugs and implement
all feature requests immediately, but I have a job and I'm doing my best to
maintain this library for over **eight** years now.

Please stay respectful and patient. I'm doing my best to keep this alive and
maintained in my free time without getting paid for it.

Well crafted merge requests are the fastest way to get your feature into
Dropzone!

<!-- 

**Dropzone 5.2.0**

The most requested feature of this release is **chunked uploads**! Thanks to
**SIMPEL** for donating the money, making this feature available to everybody!
Check out [the wiki on chunked uploads](https://gitlab.com/meno/dropzone/wikis/faq#chunked-uploads) for more
information and see the [full CHANGELOG on GitLab](https://gitlab.com/meno/dropzone/blob/master/CHANGELOG.md).

<p style="text-align: center;">
  <a href="http://simpel.com.au/" target="_blank" rel="nofollow noopener" style="border-bottom: none; background: white; padding: 0.8rem 1rem 0.5rem 0.9rem; display: inline-block;">
    <img src="https://i.imgur.com/hih5Bka.jpg" alt="SIMPEL Company Logo" style="width: 240px; height: 53px">
  </a>
</p>

**Dropzone 5.0.0**

Big shout out to MD Systems, who donated the money to make **browser side image resizing** available to everybody!

<p style="text-align: center;">
  <a href="https://www.md-systems.ch/" target="_blank" rel="nofollow noopener" style="border-bottom: none;"><svg style="width: 12em; height: 1.52em;" xmlns="http://www.w3.org/2000/svg" width="1708.859" height="219.627" viewBox="0 0 1708.859 219.627"><filter id="a" color-interpolation-filters="sRGB"><feFlood flood-color="#000" flood-opacity=".294" result="flood"/><feComposite in="flood" in2="SourceGraphic" operator="in" result="composite1"/><feGaussianBlur in="composite1" stdDeviation="2" result="blur"/><feOffset dy="1" dx="2" result="offset"/><feComposite in="SourceGraphic" in2="offset" result="composite2"/></filter><g filter="url(#a)" transform="translate(734.785 -221.68)"><path fill="#A7A48B" d="M-715.679 440.109c-5.528-1.764-11.9-7.242-14.618-12.568-2.375-4.654-2.488-7.432-2.488-61.242 0-63.427.308-66.375 8.855-84.787 15.099-32.524 41.864-52.731 77.621-58.6 29.471-4.838 63.47 4.839 87.3 24.847l8.917 7.487 6.466-6.086c12.343-11.62 24.323-18.402 41.707-23.612 9.2-2.757 13.577-3.318 26.634-3.413 8.792-.063 18.905.61 23.125 1.54 38.608 8.507 69.725 37.049 80.802 74.115 2.496 8.354 2.78 12.558 3.261 48.212l.526 39.062h54.697c51.482 0 55.125-.146 61.979-2.506 10.666-3.67 16.562-7.53 25.123-16.456 8.44-8.797 11.692-14.333 14.897-25.356 7.181-24.702-8.288-50.583-36.391-60.881-6.707-2.458-10.672-2.78-42.396-3.443-37.546-.785-39.016-1.039-45.167-7.8-5.263-5.786-7.006-10.96-6.479-19.231.68-10.675 5.021-17.184 14.296-21.43l6.843-3.133 39.003.544c34.835.486 40.041.828 48.72 3.2 19.901 5.439 40.812 18.87 53.457 34.337 7.81 9.55 17.905 29.772 20.734 41.531 3.1 12.881 2.778 36.994-.662 50-9.649 36.459-36.751 66.275-70.746 77.838l-10 3.401-78.75.396c-54.225.272-80.192-.027-83.381-.966-6.253-1.837-12.116-7.001-14.895-13.118-2.088-4.598-2.297-9.098-2.322-50.101-.021-35.831-.409-46.515-1.892-52.208-5.226-20.063-20.479-36.686-39.227-42.748-9.841-3.182-23.877-2.15-33.271 2.446-12.672 6.2-24.576 20.861-29.482 36.311-1.123 3.537-1.799 20.214-2.309 56.983l-.721 51.986-3.579 5.159c-4.019 5.795-14 11.498-20.104 11.486-11.207-.021-22.799-8.244-25.541-18.121-.902-3.25-1.389-21.44-1.394-52.054-.01-43.228-.207-47.7-2.462-55-4.725-15.289-16.781-29.366-31.186-36.415-7.605-3.722-9.188-4.029-20.734-4.029-11.095 0-13.283.385-19.468 3.425-12.872 6.325-23.918 19.567-28.945 34.7-2.536 7.634-2.741 11.236-3.393 59.584l-.693 51.457-3.75 5.307c-2.062 2.918-5.924 6.428-8.582 7.801-5.464 2.827-14.694 3.82-19.935 2.149z"/><path d="M-103.635 432.574c-23.302-6.107-33.929-15.818-28.596-26.132 3.938-7.614 8.184-8.028 20.875-2.042 12.13 5.721 22.076 8.164 33.235 8.164 10.315 0 20.681-3.062 27.208-8.041 6.044-4.609 10.629-14.625 10.596-23.143-.062-15.609-7.895-23.741-35.604-36.965-10.54-5.029-22.162-11.067-25.828-13.417-9.293-5.958-17.481-14.654-21.771-23.119-3.444-6.802-3.644-8.034-3.644-22.815 0-14.714.205-16.014 3.516-22.3 9.975-18.935 28.812-28.906 54.609-28.906 17.067 0 38.384 6.544 43.817 13.451 3.519 4.473 3.282 12.77-.462 16.288-3.74 3.516-8.269 3.438-15.586-.268-26.516-13.427-54.485-7.136-59.057 13.281-1.28 5.721-1.201 7.861.508 13.738 3.211 11.048 10.673 16.923 39.736 31.287 17.666 8.73 26.037 13.628 31.123 18.207 13.028 11.728 18.47 27.485 16.074 46.561-2.877 22.912-19.45 40.435-44.231 46.761-10.729 2.738-34.991 2.431-46.518-.59zm284.948.088c-25.212-6.195-36.839-18.801-26.694-28.941 4.146-4.146 9.198-4.77 13.615-1.676 1.557 1.091 7.445 3.686 13.092 5.767 22.89 8.438 46.791 5.067 57.115-8.062 3.419-4.345 6.273-12.676 6.267-18.278-.024-15.769-7.575-23.386-37.691-38.022-25.845-12.562-35.006-19.006-42.078-29.596-6.689-10.02-8.238-15.623-8.13-29.412.114-14.388 3.255-23.068 11.681-32.287 10.899-11.927 27.229-18.304 46.854-18.298 19.068.006 41.045 7.313 45.001 14.962 2.812 5.438 2.362 10.873-1.194 14.43-4.116 4.116-6.834 3.889-19.381-1.62-10.115-4.441-11.365-4.688-23.801-4.688-11.054 0-13.914.425-18.125 2.691-6.672 3.591-10.146 7.513-12.458 14.064-2.529 7.169-2.383 13.349.466 19.623 4.303 9.474 11.368 14.631 38.338 27.984 28.763 14.24 37.123 20.812 43.745 34.388 3.429 7.024 3.658 8.451 3.658 22.563 0 14.896-.053 15.173-4.698 24.572-7.628 15.435-20.754 25.639-39.002 30.324-10.37 2.662-34.804 2.406-46.58-.488zm704.023 1.567c-17.012-3.708-31.203-10.575-34.946-16.91-2.852-4.827-1.683-11.284 2.661-14.7 4.054-3.188 8.638-3.244 13.688-.166 8.156 4.976 22.148 9.115 33.041 9.778 24.587 1.498 40.353-9.142 42.1-28.409 1.553-17.119-5.909-25.141-37.757-40.588-29.539-14.328-40.33-23.102-46.463-37.779-3.162-7.568-4.372-19.587-2.9-28.801 4.259-26.659 26.394-42.796 58.704-42.796 16.924 0 36.42 5.965 43.116 13.192 6.225 6.715 2.479 19.264-5.75 19.264-2.034 0-6.377-1.356-9.649-3.015-10.547-5.345-19.63-7.332-30.728-6.722-11.72.644-18.916 3.703-23.619 10.038-9.045 12.182-7.687 24.624 3.935 35.991 5.885 5.758 11.212 8.962 31.783 19.119 27.53 13.593 35.987 20.163 42.927 33.353 3.442 6.545 3.61 18.773 3.61 23.111s-.068 16.385-4.257 24.732c-7.38 14.707-21.685 25.668-39.443 30.229-6.992 1.795-33.492 2.51-40.053 1.079zM61.92 430.168l-4.082-3.646-.625-36.042-.625-36.042-26.213-52.185L4.163 250.07 6 244.754c3.281-9.493 14.681-12.357 21.396-5.377 2.797 2.905 28.138 54.872 37.517 76.937 2.774 6.531 5.438 12.293 5.915 12.804.477.51 3.055-4.271 5.729-10.625 10.123-24.06 35.92-76.658 38.925-79.366 3.729-3.361 12.228-3.828 16.404-.9 1.501 1.051 3.295 3.958 3.985 6.458 1.628 5.898-.583 10.97-30.146 69.13L83.172 358.19l.888 30.875c.644 22.312.483 32.099-.568 35.292-3.209 9.712-13.961 12.609-21.572 5.811zm290.243 1.819c-6.311-3.433-6.21-2.063-6.527-90.048l-.299-82.5-26.821-.338c-25.171-.317-26.992-.498-29.582-2.931-3.64-3.419-4.715-8.147-2.867-12.607 3.026-7.307 2.438-7.249 73.487-7.249h64.966l3.849 3.236c5.061 4.258 5.409 11.562.775 16.196-3.065 3.068-3.071 3.068-30 3.068h-26.932v166.5l-4.25 4.25c-4.706 4.706-10.086 5.531-15.799 2.423zm258.798.227c-1.719-.857-4.114-3.521-5.323-5.918-2.047-4.059-2.177-10.562-1.875-94.153l.323-89.796 3.652-3.142c3.53-3.037 4.136-3.125 18.125-2.657 15.52.52 20.854 2.194 24.441 7.671 1.028 1.569 14.856 35.724 30.729 75.9 15.872 40.175 28.981 73.169 29.134 73.32s13.749-32.439 30.22-72.424c16.471-39.985 31.083-74.414 32.471-76.512 4.237-6.399 9.5-8.185 24.136-8.187 12.603-.002 12.996.085 16.562 3.652l3.654 3.654v181.692l-4.25 4.25c-3.062 3.061-5.368 4.25-8.245 4.25-4.41 0-10.636-3.168-12.153-6.184-.537-1.068-1.258-39.166-1.602-84.663l-.625-82.722-34.254 84.973c-23.298 57.791-35.082 85.552-36.841 86.783-3.061 2.143-15.545 2.436-19.865.467-2.485-1.133-8.082-14.666-35.371-85.538l-32.419-84.193-.625 80.851c-.479 61.703-.997 81.504-2.197 83.602-3.556 6.215-11.136 8.356-17.802 5.024zm-151.423-2.041l-2.951-2.389-.337-91.043c-.238-64.342.066-92.021 1.045-94.38 2.453-5.922 4.758-6.165 54.768-5.782l46.618.357 3.018 3.507c3.282 3.82 3.836 8.242 1.562 12.513-3.039 5.705-3.541 5.773-42.607 5.815l-37.188.04v61.521l31.771-.448 31.771-.448 3.229 3.03c4.402 4.131 4.479 11.461.162 15.775l-3.067 3.068h-63.866v68.646l38.234.361 38.233.365 3.017 3.507c3.282 3.819 3.836 8.242 1.562 12.515-3.088 5.797-2.871 5.771-53.72 5.813-45.726.046-48.461-.079-51.254-2.343z"/></g></svg></a>
</p> -->


</section>

{% include _meno_plug.html %}


<section markdown="1">
# Installation

You probably only need to look at the [simple example](http://www.dropzonejs.com/examples/simple.html) ([source](https://gitlab.com/meno/dropzone/raw/master/website/examples/simple.html))
to get started. Continue reading for step by step instructions and different
installation approaches.

* * *

Download the standalone [dropzone.js](https://github.com/enyo/dropzone/archive/v5.7.0.zip)
and include it like this:

{% highlight html %}
<script src="./path/to/dropzone.js"></script>
{% endhighlight %}

Dropzone is now activated and available as `window.Dropzone`.

> Dropzone does *not* handle your file uploads on the server. You have to implement
> the code to receive and store the file yourself. See the section
> [Server side implementation](#server-side-implementation) for more information.

This is all you need to get dropzone up and running, but if you want it to look
like the dropzone on this page, you’ll need to use the **dropzone.css**
in the [dist folder](https://github.com/enyo/dropzone/archive/v5.7.0.zip).


With RequireJS
--------------

Dropzone is also available as an [AMD module](https://github.com/amdjs/amdjs-api/wiki/AMD)
for [RequireJS](http://requirejs.org).

You can find the [dropzone-amd-module](https://github.com/enyo/dropzone/archive/v5.7.0.zip)
in the dist folder.




</section>

<section markdown="1">
# Usage

The typical way of using dropzone is by creating a form element with the class `dropzone`:

{% highlight html %}
<form action="/file-upload"
      class="dropzone"
      id="my-awesome-dropzone"></form>
{% endhighlight %}

That’s it. Dropzone will find all form elements with the class dropzone,
automatically attach itself to it, and upload files dropped into it to the
specified `action` attribute. The uploaded files can be handled just as if
there would have been a html input like this:

{% highlight html %}
<input type="file" name="file" />
{% endhighlight %}

If you want another name than `file` you can [configure dropzone](#configuration)
with the option `paramName`.


If you want your file uploads to work even without JavaScript, you can include
an element with the class `fallback` that dropzone will remove if the browser
is supported. If the browser isn’t supported, Dropzone will not create fallback
elements if there is a fallback element already provided. (Obviously, if the
browser doesn’t support JavaScript, the form will stay as is)

Typically this will look like this:

{% highlight html %}
<form action="/file-upload" class="dropzone">
  <div class="fallback">
    <input name="file" type="file" multiple />
  </div>
</form>
{% endhighlight %}



Create dropzones programmatically
---------------------------------

Alternatively you can create dropzones programmaticaly (even on non `form`
elements) by instantiating the `Dropzone` class

{% highlight js %}
// Dropzone class:
var myDropzone = new Dropzone("div#myId", { url: "/file/post"});
{% endhighlight %}

or if you use jQuery, you can use the jQuery plugin Dropzone ships with:

{% highlight js %}
// jQuery
$("div#myId").dropzone({ url: "/file/post" });
{% endhighlight %}

> Don’t forget to specify an `url` option if you’re not using a form element,
> since Dropzone doesn’t know where to post to without an `action` attribute.



Server side implementation
--------------------------

Dropzone does *not* provide the server side implementation of handling the files,
but the way files are uploaded is identical to simple file upload forms like this:

{% highlight html %}
<form action="" method="post" enctype="multipart/form-data">
  <input type="file" name="file" />
</form>
{% endhighlight %}

To handle basic file uploads on the server, please look at the corresponding
documentation. Here are a few documentations, if you think I should add some,
please contact me.

- [AngularJS and Spring](http://www.cantangosolutions.com/blog/Easy-File-Upload-Using-DropzoneJS-AngularJs-And-Spring)
- [NodeJS with express](http://howtonode.org/really-simple-file-uploads)
- [Ruby on rails](http://guides.rubyonrails.org/form_helpers.html#uploading-files)
- [Complete PHP tutorial](http://www.startutorial.com/articles/view/how-to-build-a-file-upload-form-using-dropzonejs-and-php) by startutorial.com
- [Basic PHP file upload](http://www.php.net/manual/en/features.file-upload.post-method.php#example-354)
- [Tutorial for Dropzone and Lavarel (PHP)](http://maxoffsky.com/code-blog/howto-ajax-multiple-file-upload-in-laravel/) written by Maksim Surguy
- [Symfony2 and Amazon S3](http://www.jesuisundev.fr/upload-drag-drop-via-dropzonejs-symfony2-on-cloud-amazon-s3/)
- [File upload in ASP.NET MVC using Dropzone JS and HTML5](http://venkatbaggu.com/file-upload-in-asp-net-mvc-using-dropzone-js-and-html5/)
- [Servicestack and Dropzone](http://www.buildclassifieds.com/2016/01/08/uploading-images-servicestack-and-dropzone/)
- [How to build a file upload form using DropzoneJS and Go](https://hackernoon.com/how-to-build-a-file-upload-form-using-dropzonejs-and-go-8fb9f258a991)
- [How to display existing files on server using DropzoneJS and Go](https://hackernoon.com/how-to-display-existing-files-on-server-using-dropzonejs-and-go-53e24b57ba19)

Paid documentations:

- [eBook for Dropzone with PHP](http://www.startutorial.com/homes/dropzonejs_php_the_complete_guide?utm_source=dzj&amp;utm_medium=banner&amp;utm_campaign=dropzonejs) by startutorial.com.


Please look at the [Dropzone FAQ](https://gitlab.com/meno/dropzone/-/wikis/FAQ) if
you need more information.





</section>

<section markdown="1">
# Configuration

There are two ways to configure dropzones.

The obvious way is to pass an options object when instantiating a dropzone
programmatically like in the previous [create dropzones programmatically](#create-dropzones-programmatically)
section.

But if you just have HTML elements with the `dropzone` class, then you don’t
programmatically instantiate the objects, so you have to store the configuration
somewhere so Dropzone knows how to configure the dropzones when instantiating
them.

This is done with the `Dropzone.options` object.

{% highlight js %}
// "myAwesomeDropzone" is the camelized version of the HTML element's ID
Dropzone.options.myAwesomeDropzone = {
  paramName: "file", // The name that will be used to transfer the file
  maxFilesize: 2, // MB
  accept: function(file, done) {
    if (file.name == "justinbieber.jpg") {
      done("Naha, you don't.");
    }
    else { done(); }
  }
};
{% endhighlight %}


If you want to disable the auto discover behaviour of Dropzone, you can either disable
it on a per element basis, or in general:

{% highlight js %}
// Prevent Dropzone from auto discovering this element:
Dropzone.options.myAwesomeDropzone = false;
// This is useful when you want to create the
// Dropzone programmatically later

// Disable auto discover for all elements:
Dropzone.autoDiscover = false;
{% endhighlight %}


{% include configuration-options.html %}


> You can also overwrite all default event actions in the options. So if you provide the option `drop` you can overwrite the default `drop` event handler.
> *You should be familiar with the code if you do that because you can easily break the upload like this.*
> If you just want to do additional stuff, like adding a few classes here and there, **[listen to the events](#events) instead**!


## Enqueuing file uploads

When a file gets added to the dropzone, its `status` gets set to `Dropzone.QUEUED`
(after the `accept` function check passes) which means that the file is now
in the queue.

If you have the option `autoProcessQueue` set to `true` then the queue is immediately
processed, after a file is dropped or an upload finished, by calling
`.processQueue()` which checks how many files are currently uploading,
and if it’s less than `options.parallelUploads`, `.processFile(file)` is called.

If you set `autoProcessQueue` to `false`, then `.processQueue()` is never called
implicitly. This means that you have to call it yourself when you want to
upload all files currently queued.



## Layout

The HTML that is generated for each file by dropzone is defined with the option `previewTemplate` which defaults to this:

{% highlight html %}
<div class="dz-preview dz-file-preview">
  <div class="dz-details">
    <div class="dz-filename"><span data-dz-name></span></div>
    <div class="dz-size" data-dz-size></div>
    <img data-dz-thumbnail />
  </div>
  <div class="dz-progress"><span class="dz-upload" data-dz-uploadprogress></span></div>
  <div class="dz-success-mark"><span>✔</span></div>
  <div class="dz-error-mark"><span>✘</span></div>
  <div class="dz-error-message"><span data-dz-errormessage></span></div>
</div>
{% endhighlight %}

The container (`dz-preview`) gets the `dz-processing` class when the file gets processed, `dz-success` when the file got uploaded and `dz-error` in case the file couldn’t be uploaded.
In the latter case, `data-dz-errormessage` will contain the text returned by the server.

To overwrite the default template, use the [`previewTemplate`](#config-previewTemplate)
config.

You can access the HTML of the file preview in any of the events with `file.previewElement`.

If you decide to rewrite the `previewTemplate` from scratch, you should put elements with the `data-dz-*` attributes inside:

- `data-dz-name`
- `data-dz-size`
- `data-dz-thumbnail` (This has to be an `<img />` element and the `alt` and `src` attributes will be changed by Dropzone)
- `data-dz-uploadprogress` (Dropzone will change the `style.width` property from `0%` to `100%` whenever there’s a `uploadprogress` event)
- `data-dz-errormessage`

The default options for Dropzone will look for those element and update the content for it.

If you want some specific link to remove a file (instead of the built in [`addRemoveLinks`](#config-addRemoveLinks) config), you can simply insert elements
in the template with the `data-dz-remove` attribute. Example:

{% highlight html %}
<img src="removebutton.png" alt="Click me to remove the file." data-dz-remove />
{% endhighlight %}

You are not forced to use those conventions though. If you override all the default event listeners
you can completely rebuild your layout from scratch.

See the installation section on how to add the stylesheet and spritemaps if you want your dropzone to look like the one on this page.

See the [Theming](#theming) section, for a more in depth look at how to change Dropzone’s UI.

I created an example where I made Dropzone look and feel exactly the way jQuery
File Uploader does with a few lines of configuration code. [Check it out!](/bootstrap.html)

> Again, please look at the [Dropzone FAQ](https://gitlab.com/meno/dropzone/-/wikis/FAQ) if
> you’re still unclear about some features.



## Dropzone methods

If you want to remove an added file from the dropzone, you can call `.removeFile(file)`.
This method also triggers the `removedfile` event.

Here’s an example that would automatically remove a file when it’s finished uploading:

{% highlight js %}
myDropzone.on("complete", function(file) {
  myDropzone.removeFile(file);
});
{% endhighlight %}

If you want to remove all files, simply use `.removeAllFiles()`. Files that are
in the process of being uploaded won’t be removed. If you want files that are
currently uploading to be canceled, call `.removeAllFiles(true)` which will
cancel the uploads.

* * *

If you have `autoProcessQueue` disabled, you’ll need to call `.processQueue()`
yourself.

This can be useful if you want to display the files and let the user click an
accept button to actually upload the file(s).

* * *

To access all files in the dropzone, use `myDropzone.files`.

To get

- all accepted files: `.getAcceptedFiles()`
- all rejected files: `.getRejectedFiles()`
- all queued files: `.getQueuedFiles()`
- all uploading files: `.getUploadingFiles()`

* * *

If you do not need a dropzone anymore, just call `.disable()` on the object. This
will remove all event listeners on the element, and clear all file arrays. To
reenable a Dropzone use `.enable()`.

* * *

If you don’t like the default browser modals for `confirm` calls,
you can handle them yourself by overwriting `Dropzone.confirm`.

{% highlight js %}
Dropzone.confirm = function(question, accepted, rejected) {
  // Ask the question, and call accepted() or rejected() accordingly.
  // CAREFUL: rejected might not be defined. Do nothing in that case.
};
{% endhighlight %}

* * *

If you want Dropzone to display an image you have on your server, you can use:

{% highlight js %}
// callback and crossOrigin are optional
let mockFile = { name: "Filename", size: 12345 };
myDropzone.displayExistingFile(mockFile, 'https://image-url');
{% endhighlight %}

See the FAQ on [How to show files stored on server](https://gitlab.com/meno/dropzone/-/wikis/FAQ#how-to-show-files-already-stored-on-server)
 for more information.




</section>

<section markdown="1">
# Events

Dropzone triggers events when processing files, to which you can register easily,
by calling `.on(eventName, callbackFunction)` on your _instance_.

Since listening to events can only be done on _instances_ of Dropzone, the best
place to setup your event listeners, is in the `init` function:

{% highlight js %}
// The recommended way from within the init configuration:
Dropzone.options.myAwesomeDropzone = {
  init: function() {
    this.on("addedfile", function(file) { alert("Added file."); });
  }
};
{% endhighlight %}

If you [create your Dropzones programmatically](#create-dropzones-programmatically),
you can setup your event listeners on your instances, like this:

{% highlight js %}
// This example uses jQuery so it creates the Dropzone, only when the DOM has
// loaded.

// Disabling autoDiscover, otherwise Dropzone will try to attach twice.
Dropzone.autoDiscover = false;
// or disable for specific dropzone:
// Dropzone.options.myDropzone = false;

$(function() {
  // Now that the DOM is fully loaded, create the dropzone, and setup the
  // event listeners
  var myDropzone = new Dropzone("#my-dropzone");
  myDropzone.on("addedfile", function(file) {
    /* Maybe display some more file information on your page */
  });
})
{% endhighlight %}

This is a bit more complex, and not necessary unless you have a good reason
to instantiate Dropzones programmatically.

> Dropzone itself relies heavily on events. Everything that’s visual is created
by listening to them. Those event listeners are setup in the default configuration
of every Dropzone and can be overwritten, thus replacing the default behavior
with your own event callback.

You should only do this when you really know how Dropzone works, and when you
want to [completely theme your Dropzone](#theming)


{% include event-list.html %}


## Theming

If you want to theme your Dropzone to look fully customized, in most cases you
can simply [replace the preview HTML template](#layout), adapt your CSS, and maybe create
a few additional event listeners.

You will go very far with this approach. As an example, I created an example
where I made Dropzone look and feel exactly the way jQuery File Uploader does
with a few lines of configuration code. [Check it out!](/bootstrap.html)

As you can see, the biggest change is the `previewTemplate`. I then added a few
additional event listeners to make it look exactly like the reference.

*You can however, implement your UI completely from scratch.*

Dropzone itself sets up a lot of event listeners when a Dropzone is created,
that handle all your UI. They do stuff like: create a new HTML element,
add the `<img>` element when provided with image data (with the [`thumbnail`](#event-thumbnail) event),
update the progress bar when the [`uploadprogress`](#event-uploadprogress) event fires,
show a checkmark when the [`success`](#event-success) event fires,
etc...


_Everything_ visual is done in those event handlers. If you would overwrite all
of them with empty functions, Dropzone
would still be fully functional, but wouldn’t display the dropped files anymore.

> If you like the default look of Dropzone, but would just like to add a few
> bells and whistles here and there, you should just [add additional event 
> listeners](#events) instead.

Overwriting the default event listeners, and creating your own, custom Dropzone,
would look something like this:


{% highlight js %}
// This is an example of completely disabling Dropzone's default behavior.
// Do *not* use this unless you really know what you are doing.
Dropzone.myDropzone.options = {
  previewTemplate: document.querySelector('#template-container').innerHTML,
  // Specifing an event as an configuration option overwrites the default
  // `addedfile` event handler.
  addedfile: function(file) {
    file.previewElement = Dropzone.createElement(this.options.previewTemplate);
    // Now attach this new element some where in your page
  },
  thumbnail: function(file, dataUrl) {
    // Display the image in your file.previewElement
  },
  uploadprogress: function(file, progress, bytesSent) {
    // Display the progress
  }
  // etc...
};
{% endhighlight %}

Obviously this lacks the actual implementation. Look at the source to see how
Dropzone does it internally.

You should use this option if you don’t need any of the default Dropzone UI,
but are only interested in Dropzone for it’s event handlers, file upload and
drag’n’drop functionality.



</section>

<section markdown="1">
# Tips

If you do not want the default message at all (»Drop files to upload (or click)«), you can
put an element inside your dropzone element with the class `dz-message` and dropzone
will not create the message for you.

* * *

Dropzone will submit any hidden fields you have in your dropzone form. So this
is an easy way to submit additional data. You can also use the `params` option.

* * *

Dropzone adds data to the `file` object you can use when events fire. You can
access `file.width` and `file.height` if it’s an image, as well as
`file.upload` which is an object containing: `progress` (0-100), `total` (the
total bytes) and `bytesSent`.

* * *

If you want to add additional data to the file upload that has to be specific for
each file, you can register for the [`sending`](#event-sending) event:

{% highlight js %}
myDropzone.on("sending", function(file, xhr, formData) {
  // Will send the filesize along with the file as POST data.
  formData.append("filesize", file.size);
});
{% endhighlight %}

* * *

To access the preview html of a file, you can access `file.previewElement`. For
example:

{% highlight js %}
myDropzone.on("addedfile", function(file) {
  file.previewElement.addEventListener("click", function() {
    myDropzone.removeFile(file);
  });
});
{% endhighlight %}

* * *

If you want the whole body to be a Dropzone and display the files somewhere else
you can simply instantiate a Dropzone object for the body, and define the
[`previewsContainer`](#config-previewsContainer) option. The `previewsContainer` should have the
`dropzone-previews` or `dropzone` class to properly display the file previews.

{% highlight js %}
new Dropzone(document.body, {
  previewsContainer: ".dropzone-previews",
  // You probably don't want the whole body
  // to be clickable to select files
  clickable: false
});
{% endhighlight %}



Look at the [gitlab wiki](https://gitlab.com/meno/dropzone/wikis/home) for more examples.

If you have any problems using Dropzone, please try to find help on
[stackoverflow.com](https://stackoverflow.com/questions/tagged/dropzone.js) by using the `dropzone.js`
tag.
Only create an issue on GitLab when you think you found a bug or want to
suggest a new feature.



</section>

<section markdown="1">
# Compatibility

This section describes compatibility with browsers and older versions of
Dropzone.

Browser Support
---------------

- Chrome 7+
- Firefox 4+
- IE 10+
- Opera 12+ (Version 12 for MacOS is disabled because their API is buggy)
- Safari 6+

For all the other browsers, dropzone provides an oldschool file input fallback.

There is no workaround for drag’n’drop in older browsers – it simply isn't
supported. The same goes for image previews, etc... But using dropzone, your
users using an old browser _will_ be able to upload files. It just won’t look
and feel great. But hey, that’s their fault.

Version 5.0
---------

- Starting with version 5.2, dropzone is no longer written in CoffeeScript, but in EcmaScript6. To
  still work in older browsers, the code is still compiled with babel.

Version 4.0
-----------

<aside>This is not a changelog. Only compatibility problems are listed.</aside>

- Changed the default [`previewTemplate`](#config-previewTemplate). Check out the
  new one in the [layout section](#layout).
- Using an already included SVG instead of a PNG spritemap (the CSS file is now
  the only additional file that you need to include)


Version 3.0
-----------

<aside>This is not a changelog. Only compatibility problems are listed.</aside>

- All classes are prefixed with `dz-` now to prevent clashing with other CSS definitions
- The way `previewTemplate` is defined has changed. You have to provide `data-dz-*` elements now
- If the server returns JSON, it will be parsed for error messages as well
- There’s a `dict*` option for all of the visible messages
- Lots of minor fixes and changes

Version 2.0
-----------

<aside>This is not a changelog. Only compatibility problems are listed.</aside>

Starting with version 2.0, Dropzone no longer depends on jQuery, but Dropzone
still registers itself as a jQuery module if available.

That means that creating your Dropzones like this still works:

{% highlight js %}
$("#my-dropzone").dropzone({ /* options */ });
{% endhighlight %}

If you create your Dropzones with the normal constructor though, you have to
pass either the raw HTMLElement, or a selector string. So those versions all
work:

{% highlight js %}
// With jQuery
new Dropzone($("#my-dropzone").get(0));
// Without jQuery
new Dropzone("#my-dropzone");
new Dropzone(document.querySelector("#my-dropzone"));
{% endhighlight %}

Another thing that changed, is that Dropzone no longer stores its instances
inside the element’s data property. So to get a dropzone for an element do this
now:

{% highlight js %}
// DEPRECATED, do not use:
$("#my-dropzone").data("dropzone"); // won't work anymore
// Do this now:
Dropzone.forElement(element); // Providing a raw HTMLElement
// or
Dropzone.forElement("#my-dropzone"); // Providing a selector string.
{% endhighlight %}



</section>




<section markdown="1">

Donate
======

Please consider donating if you like this project. I’ve put a lot of my free
time into this project and donations help to justify it.


<div>
Use the Paypal

<form class="donate" action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_s-xclick">
<input type="hidden" name="hosted_button_id" value="CA598M5X362GQ">
<input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
<img alt="" border="0" src="https://www.paypalobjects.com/de_DE/i/scr/pixel.gif" width="1" height="1">
</form>

button, <a href="http://tiptheweb.org/">tiptheweb</a> or my
<a href="http://bitcoin.org/">Bitcoin</a> address:
<div class="bitcoin"><code>17nRfhRyaKAn93xmB7SQm9sX8fNUtc66YZ</code></div>.
</div>

</section>

