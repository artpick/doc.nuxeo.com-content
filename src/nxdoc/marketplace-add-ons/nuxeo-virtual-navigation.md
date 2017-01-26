---
title: Nuxeo Virtual Navigation
review:
    comment: ''
    date: ''
    status: ok
labels:
    - lts2015-ok
    - virtual-navigation-component
    - virtual-navigation
toc: true
confluence:
    ajs-parent-page-id: '28475782'
    ajs-parent-page-title: Marketplace Add-Ons
    ajs-space-key: NXDOC710
    ajs-space-name: Nuxeo Platform Developer Documentation — LTS 2015
    canonical: Nuxeo+Virtual+Navigation
    canonical_source: 'https://doc.nuxeo.com/display/NXDOC710/Nuxeo+Virtual+Navigation'
    page_id: '28475671'
    shortlink: F4GyAQ
    shortlink_source: 'https://doc.nuxeo.com/x/F4GyAQ'
    source_link: /display/NXDOC710/Nuxeo+Virtual+Navigation
history:
    - 
        author: Anonymous
        date: '2015-11-18 14:48'
        message: oved description from "How to Add a New Virtual Navigation Entry
        version: '7'
    - 
        author: Solen Guitter
        date: '2014-11-28 18:23'
        message: ''
        version: '6'
    - 
        author: Solen Guitter
        date: '2014-11-28 18:23'
        message: merging all docs about this add-on
        version: '5'
    - 
        author: Solen Guitter
        date: '2014-11-28 18:12'
        message: ''
        version: '4'
    - 
        author: Solen Guitter
        date: '2014-11-03 16:43'
        message: Add links
        version: '3'
    - 
        author: Solen Guitter
        date: '2014-10-27 11:41'
        message: ''
        version: '2'
    - 
        author: Solen Guitter
        date: '2014-10-27 11:34'
        message: ''
        version: '1'

---
{{! excerpt}}

A virtual navigation entry is a tab, just beside the browsing tree, that displays a hierarchical tree representing your vocabulary values. Clicking on one of the values will filter the repository content to display only documents having that value for one of its metadata (depending on the configured query). We call it "Virtual navigation", in opposition to the real filing position, in the folders tree.

The Nuxeo Virtual Navigation add-on provides two navigation trees based on the Subjects and Coverage metadata instead of the folder structure.

{{! /excerpt}}

&nbsp;

## Installation

The Nuxeo Virtual Navigation add-on requires no specific installation steps. It can be installed like any other package [from the Update Center or from the Marketplace]({{page space='admindoc710' page='installing-a-new-package-on-your-instance'}}).

After it is installed, two new tabs are available in the Workspace tab left panel:

![]({{file name='virtual_navigation.png'}} ?w=250,border=true,thumbnail=true)

## Functional Overview

Coverage virtual navigation uses the continent and country vocabularies; The Subjects virtual navigation relies on the topic and subtopic vocabularies.

To browse documents, click on a tree item.

## Customization

You can customize the virtual navigation default behavior:

*   [How to Disable by Coverage and by Subjects Virtual Navigations]({{page page='how-to-disable-by-coverage-and-by-subjects-virtual-navigations'}})
*   [How to Add a New Virtual Navigation Entry]({{page page='how-to-add-a-new-virtual-navigation-entry'}})

&nbsp;

* * *

<div class="row" data-equalizer data-equalize-on="medium"><div class="column medium-6">{{#> panel heading='Related How-Tos'}}

*   [How to Disable by Coverage and by Subjects Virtual Navigations]({{page page='how-to-disable-by-coverage-and-by-subjects-virtual-navigations'}})
*   [How to Add a New Virtual Navigation Entry]({{page page='how-to-add-a-new-virtual-navigation-entry'}})
*   [How-To Index]({{page page='how-to-index'}})

{{/panel}}</div><div class="column medium-6">{{#> panel heading='Related Documentation'}}

*   [Virtual Navigations in Nuxeo Studio]({{page space='studio' page='virtual-navigations'}})
*   [Content Views developer documentation]({{page page='content-views'}})

{{/panel}}</div></div>