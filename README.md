# kali-docker-image
<p>This image is not tracking kali-rolling but kali-last-snapshot which contains a snapshot of the kali-rolling repository at the time of the last official release (eg. 2019.3, 2019.4, etc.). <strong>You don't get any updates when you use that image</strong> but you should have a working distribution, albeit not fully up-to-date.</p>
<p>Please note, there are <strong>no tools by default</strong>. Instead, either do:</p>
<ul>
<li><code>apt update &amp;&amp; apt -y install &lt;package&gt;</code></li>
<li><code>apt update &amp;&amp; apt -y install kali-linux-headless</code></li>
<li><code>apt update &amp;&amp; apt -y install kali-linux-large</code></li>
</ul>
<h3>More Information</h3>
<ul>
<li><a href="https://www.kali.org/docs/containers/official-kalilinux-docker-images/" rel="nofollow noopener">Breakdown of all Kali's Docker Images</a></li>
<li><a href="https://www.kali.org/docs/containers/using-kali-docker-images/" rel="nofollow noopener">Using Kali's Docker Image</a></li>
<li><a href="https://www.kali.org/docs/general-use/kali-branches/" rel="nofollow noopener">An explanation of Kali's branches</a></li>
<li><a href="https://www.kali.org/docs/general-use/metapackages/" rel="nofollow noopener">Breakdown of Kali's Metapackages</a></li>
<li><a href="https://gitlab.com/kalilinux/build-scripts/kali-docker" rel="nofollow noopener">Kali's Docker build script to generate the image</a></li>
<li><a href="https://www.kali.org/docs/general-use/kali-bleeding-edge/" rel="nofollow noopener">What is Kali bleeding-edge</a></li>
</ul>
