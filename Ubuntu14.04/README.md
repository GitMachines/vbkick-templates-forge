# Description

Ubuntu 14.04 [vbkick](https://github.com/wilas/vbkick) template. Help creates Vagrant base boxes. Vagrant SSH insecure keys are used.

## Howto

### change definition (change the target of a symlink)
```
    ln -fs definition-14.04-x86_64-docker.cfg definition.cfg
```

### create new vagrant base box
```
    vbkick  build        Ubuntu_box
    vbkick  postinstall  Ubuntu_box
    vbkick  validate     Ubuntu_box
    vbkick  export       Ubuntu_box
```

### update existing vagrant base box
```
    vbkick  update       Ubuntu_box
    vbkick  validate     Ubuntu_box
    vbkick  export       Ubuntu_box
```
