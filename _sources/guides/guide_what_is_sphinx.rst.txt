What is Sphinx?
===============

Sphinx lets you generate static web pages that can be hosted on sites such as `Github Pages <https://pages.github.com/>`_ and `Read the Docs <https://about.readthedocs.com/?ref=readthedocs.com>`_.
While there are other tools that can be used to generate documentation, Sphinx is **open source**, popular, and well-supported.

Some use cases for Sphinx include:


.. grid:: 2
    :gutter: 4

    .. grid-item-card::
        :class-header: `sd-bg-secondary sd-text-white sd-text-center`

        :material-regular:`dvr;2em` Documenting Code
        ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
        Sphinx can be used to generate documentation from `docstrings <https://peps.python.org/pep-0257/>`_. For example: Python's `code documentation <https://docs.python.org/3/library/functions.html#print>`_.
        

    .. grid-item-card::
        :class-header: `sd-bg-secondary sd-text-white sd-text-center`

        :material-regular:`auto_stories;2em` Knowledge Base
        ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
        Sphinx can also be used more like a wiki, where reference documents can be hosted in an accessible location.

    .. grid-item-card::
        :class-header: `sd-bg-secondary sd-text-white sd-text-center`

        :material-regular:`rss_feed;2em` Blogging
        ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
        "Blog-style" posts can be integrated into any Sphinx project using the `ABlog extension <https://pydata-sphinx-theme.readthedocs.io/en/stable/user_guide/ablog.html>`_.

    .. grid-item-card::
        :class-header: `sd-bg-secondary sd-text-white sd-text-center`

        :material-regular:`visibility;2em` Data Visualization
        ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
        Jupyter notebook visualizations can be embedded into Sphinx documentation using the `nbsphinx <https://nbsphinx.readthedocs.io/en/0.9.3/index.html>`_ extension.

    .. grid-item-card::
        :margin: 4 2 auto auto
        :class-header: `sd-bg-secondary sd-text-white sd-text-center`
        :text-align: center

        :material-regular:`image;2em` Gallery
        ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
        You can easily throw together a gallery of cards to highlight important features, links, or images. For example, `this site <https://sphinx-extensions.readthedocs.io/en/latest/>`_.

How do I use Sphinx?
====================
.. admonition:: Why reStructuredText (rST)?
    :class: sidebar note

    This demo assumes you'll be using rST to write documentation.
    While there is `support for Markdown <https://myst-parser.readthedocs.io/en/v0.17.1/sphinx/intro.html>`_, the grammar can be cumbersome when writing complicated :term:`directives<directive>`.

Sphinx can be run locally on your laptop to generate HTML files from source code, `Markdown <https://en.wikipedia.org/wiki/Markdown>`_, or `reStructredText (rST) <https://www.sphinx-doc.org/en/master/usage/restructuredtext/index.html>`_.
You can also run it remotely on GitHub by adding a post-commit hook to build documentation pushed to a repository. This will be expanded upon in a later tutorial.

.. todo::

    Add link to tutorial to build docs in GitHub

