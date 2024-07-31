Glossary
========

.. Glossary::

    Directive
        Directives are special commands that can be embedded as text into an rST document.
        They can be used to dictate how content in the document gets formatted by Sphinx. 

        For example this:

        .. code-block:: rst

            .. admonition:: title

                content

        ... would generate this:

        .. admonition:: title

            content

        For more information, see Sphinx's `Directive documentation <https://www.sphinx-doc.org/en/master/usage/restructuredtext/directives.html>`_


    Index
        An index is an :term:`rST` file used to indicate the layout of documents.
        It contains at least one :term:`toctree`.

        One index of note is the :term:`Root Index`


    rST
       reStructuredText is a plaintext markup language that Sphinx can use to generate documentation.
       This will be the standard way we write documentation in this project. Mardown is an alternative langauge.

       See this `cheat sheet <https://github.com/ralsina/rst-cheatsheet/blob/master/rst-cheatsheet.rst>`_ for the common markup used in rST files.

    Root Index
        The root index is the top-level :term:`Index` rooted in the :code:`docs/` folder located in your project.
        This index contains a :term:`toctree` that specifies the tabs in the top navigation bar.

    Role
        A role is a type of annotation used in :term:`rST` documents to indicate special formatting.
        Roles can be used inline with text. For example, :code:`\:code\:\`text\`` would evaluate to :code:`text`.

        Sphinx has some `built-in roles <https://www.sphinx-doc.org/en/master/usage/restructuredtext/roles.html>`_.
        Extensions can also add new roles. For example, `sphinx-design <https://sphinx-design.readthedocs.io/en/latest/badges_buttons.html>`_ adds roles for in-line badges and icons like this: :octicon:`report;1em;sd-text-info`.

        A :term:`Directive` can also have roles associated with it, in which case they work as "options" or "parameters". 
        For example, to add line numbers to a code block directive, you need to add the :code:`\:linenos\:` option below the declaration:

        .. code-block::
            :linenos:

            .. code-block::
                :linenos:

                Example


    toctree
        toctree (Table of Contents Tree) is a kind of :term:`directive` that is used to specify how documents should be laid out.
        Here's an example of the :term:`root index`:

        .. code-block::

            .. toctree::
                :maxdepth: 1

                guides/index
                tab_2/index
                tab_3/index


