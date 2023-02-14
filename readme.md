


# reorder

Convertigo NGX builder sample project : Reorder component.


For more technical informations : [documentation](./project.md)

- [Installation](#installation)
- [Mobile Application](#mobile-application)
    - [Pages](#pages)
        - [Page](#page)


## Installation

1. In your Convertigo Studio use `File->Import->Convertigo->Convertigo Project` and hit the `Next` button
2. In the dialog `Project remote URL` field, paste the text below:
   <table>
     <tr><td>Usage</td><td>Click the copy button</td></tr>
     <tr><td>To contribute</td><td>

     ```
     reorder=C:/Convertigo/Studio 8.1.0/workspace/reorder/.git:branch=master
     ```
     </td></tr>
     <tr><td>To simply use</td><td>

     ```
     reorder=C:/Convertigo/Studio 8.1.0/workspace/reorder//archive/master.zip
     ```
     </td></tr>
    </table>
3. Click the `Finish` button. This will automatically import the __reorder__ project


## Mobile Application

This is a sample demo project that uses the <strong>Reorder group</strong> and <strong>Reorder</strong> components.<br/>
It displays a list of fictive people you can reorder.

<ul>
<li>Click the reorder icon to enable/disable reordering on the list.</li>
<li>Drag and drop elements of the list to reorder them.</li>
<li><strong>ionItemReorder</strong> event is fired and must contain <strong>event.detail.complete()</strong> function (in a CustomAction component).</li>
<li>The people list is generated by a sequence and saved in a local page variable (<strong>page.local.people</strong>). Pass this variable to the <strong>complete()</strong> method to sync DOM and Array data when list is reordered.</li>
</ul>

### Pages

#### Page

Reorder component usage.<br/>
<img src="./doc/c8oprj-sample-reorder_group.gif" />




