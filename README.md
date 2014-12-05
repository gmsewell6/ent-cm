ent-cm
======

Has customized 'main' section of bower.json picking and choosing which sections
of codemirror to use and which should be imported in our headers & served to the client
with our non-requirejs/amd/browserify automated angular bower resource
analysis & inclusion mechanism.

To install, use:
```
$ bower install ent-cm=git@github.com:gmsewell6/ent-cm.git --save
```

To modify inclusion, change main section file reference array keeping in mind
the 'codemirror' directory relationship to this one in the codebase.
