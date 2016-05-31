Dockerfile syntax highlighting for gedit
========================================

Installation
------------

With curl

```
sudo curl -L https://github.com/kodeart/docker-gedit/archive/master.tar.gz | tar xz -C /usr/share/gtksourceview-3.0/language-specs/ --strip-components=1
```

or simply copy the `docker.lang` file in the directory `/usr/share/gtksourceview-3.0/language-specs/`.

If **gedit** is running, restart it.
