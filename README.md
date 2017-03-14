How to create a website on a configured VM
------------------------------------------
On the VM run:

```bash
bundle exec jekyll build --destination /var/www/html/<username>
```

and view your website at 

http://<ip-to-vm>/<username>

Notes about setup
-----------------
If you want to get this working on a different web-server with apache2 installed follow the setup here:
https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/


