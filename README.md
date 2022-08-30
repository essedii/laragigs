

<h1>An app for listing Laravel gigs/jobs.</h1>

<h3>1) Migrate</h3>
To create all the necessary tables and columns, run the following

<pre class="notranslate"><code>php artisan migrate
</code></pre>

<h3>2) Seeding The Database</h3>
To create all the nessesary tables and columns, run the following

<pre class="notranslate"><code>php artisan db:seed
</code></pre>

<h3>3) Link Upload</h3>
When uploading listing files, they go to "storage/app/public". Create a symlink with the following command to make them publicly accessible.

<pre class="notranslate"><code>php artisan storage:link
</code></pre>

