---
layout: page
title: "Database Version Information"
permalink: /database_version/
---
***

Here, you can find an overview of current and previous versions of the MacaqueNet database.

<iframe height="400" width="100%" frameborder="no" src="https://github.com/MacaqueNet/MacaqueNet.github.io/blob/main/version_info_from_database_internal.html"> </iframe>


<div id="embedded-content">Loading...</div>

<script>
    // Fetch the HTML content
    fetch("https://github.com/MacaqueNet/database-internal/blob/main/database%20version/NEWS.md")
        .then(response => response.text())
        .then(html => {
            document.getElementById('embedded-content').innerHTML = html;
        })
        .catch(error => {
            document.getElementById('embedded-content').innerHTML = 'Error loading content.';
            console.error('Error fetching content:', error);
        });
</script>
