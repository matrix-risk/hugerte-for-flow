# HugeRTE for Flow

Vaadin Flow Java API for HugeRTE text editor. HugeRTE is an MIT-licensed fork of TinyMCE, the world's #1 JavaScript library for rich text editing, which switched from MIT to a GPL-or-pay license model in its latest version.

This add-on is a direct port of the [TinyMCE for Flow](https://vaadin.com/directory/component/tinymce-for-flow) add-on to use HugeRTE instead. Comments in the code may though refer to previous issues in the TinyMCE add-on, as the code is mostly a copy of it.

Works with binder as the component implements HasValue interfaces. The value is plain HTML. If you can't trust your clients, consider adding a converter that filters the input with e.g. JSOUP library.
