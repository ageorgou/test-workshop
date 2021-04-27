---
layout: page
title: Setup instructions (Windows)
---
<ol>
          <li>Download the Git for Windows <a href="https://gitforwindows.org/">installer</a>.</li>
          <li>Run the installer and follow the steps below:
            <ol>
              {% comment %} Git 2.29.1 Setup {% endcomment %}
              <li>
                Click on "Next" four times (two times if you've previously
                installed Git).  You don't need to change anything
                in the Information, location, components, and start menu screens.
              </li>
              <li>
                <strong>
                  From the dropdown menu select "Use the Nano editor by default" (NOTE: you will need to scroll <emph>up</emph> to find it) and click on "Next".
                </strong>
              </li>
              {% comment %} Adjusting the name of the initial branch in new repositories {% endcomment %}
              <li>
                On the page that says "Adjusting the name of the initial branch in new repositories", ensure that
		"Let Git decide" is selected. This will ensure the highest level of compatibility for our lessons.
              </li>
              {% comment %} Adjusting your PATH environment {% endcomment %}
              <li>
                Ensure that "Git from the command line and also from 3rd-party software" is selected and
                click on "Next". (If you don't do this Git Bash will not work properly, requiring you to
                remove the Git Bash installation, re-run the installer and to select the "Git from the
                command line and also from 3rd-party software" option.)
            </li>
</ol>