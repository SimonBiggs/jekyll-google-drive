---
layout: default
header:
  image_fullwidth: unsplash-outback.jpg
permalink: /index.html
homepage: true
mediaplayer: true
# breadcrumb: true -- re enable this once these are implimented in sheets
googlesheetpull: true
googlesheetlayout: home
---

<div class="row t60">
    <div class="editor large-12 columns" style="display: none">
        <div id="authorize-div" style="display: none">
            <div class="large-12 columns">
                <button style="width:100%" class="note button radius" id="authorize-button" onclick="handleAuthClick(event)">
                    CLICK ME <br>
                    Before you can edit this page you need to authorise this
                    website to edit your Google Sheets with a google account
                    that has been given access to the website spreadsheet.
                </button>
            </div>
        </div>
        <div id="editor-div" style="display: none">
            <div class="large-12 columns">
                <textarea style="height:250" class="page_editor"></textarea>
            </div>
        </div>
    </div>
</div>

<div class="google-sheet-layout"></div>
