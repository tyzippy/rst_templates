Use substitutions for images. Don't add image references directly to topics.

Image substitutions are stored in the file ``shared/image_substitutions.rst``.

Image files (PNG) are stored in ``shared/images``.  Look for an image that fits
the need before creating a new one.

Add an image substitution to the file ``shared/image_substitutions.rst`` in the
following format.

.. |Substitution-name Image| image:: ../../shared/images/file-name.png
        :alt: Alt text describing the image.
        :width: pixels

You then add |Substitution-name Image| in the topic where you want the iamge to
be. Make sure the substitution is on its own line.

Alt text
===========

Alternative text for screen readers is required for each image. Provide text
that is useful to someone who might not be able to see the image.

.. important:: When you translate existing content, make sure you do not
   change the filepath portion of the image reference. You should only
   translate the alternative text.

   If you replace any original source images with localized images, make sure
   the replacement image files have exactly the same filenames, and replace
   them in the same Images folder location, so that image links within the
   documentation are not broken.

Width
===========

Use a width between 400 - 800, depending on the image details.  Small, focused
images are better than whole windows. You should build the document and test
images before submitting a pull request.

Image Files
============

Save images as ``.png`` files, give them a descriptive file name, and store in
``shared/image_substitutions.rst``.
