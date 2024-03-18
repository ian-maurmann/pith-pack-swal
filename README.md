# pith-pack-swal
Pack SweetAlert for front-end for Pith

-------

# About

This project packs SweetAlert2 so that it can be used with the Pith Framework.

For info about SweetAlert2, see the SweetAlert2 website at https://sweetalert2.github.io/

For info on Pith, see the Pith website at https://pith-framework.org/

# Install

Install to an existing Pith Framework project

Use Composer to install pack to the `vendor` folder.
```bash
php composer.phar require pith-front/pith-pack-swal
```

Add new route to your Route List:

```php
public array $routes = [
    // Other routes....
    // ...
    
    // Add route to call SweetAlert resources from
    ['route', 'GET', '/resources/vendor/library/sweet-alert/{filepath:.+}', '\\PithFront\\PithPackSwal\\SwalResourceRoute'],
];
```

-------------


# Licensing Info

pith-pack-swal contains SweetAlert2


### SweetAlert2
- SweetAlert2 11.7.3 
- The MIT License (MIT)
- Copyright (c) 2014 Tristan Edwards & Limon Monte 
- Website: https://sweetalert2.github.io/ 
- Repo: https://github.com/sweetalert2/sweetalert2

### Swal2 No-Anthems Edit
- Swal2 No-Anthems 11.7.3
- (SweetAlert2, with lines of junk code removed, no code added. See SweetAlert2)
- License: The MIT License (MIT)

### pith-pack-swal
- pith-pack-swal
- The MIT License (MIT)
- Copyright (c) Ian Maurmann
- Link: https://github.com/pith-front/pith-pack-swal



-------------

Thanks!