4f74325 (HEAD -> master, origin/master) Update to make use of new corp repository classes
39237e8 Update to use new classes from the the repository
db6db82 Fix middleware to include new `web` middleware.
ba92bd6 Update PHP & Laravel dependencies
dc8136f Update Form Request validation to use new base class
7ebe1db Convert `Route::controller` methods to explicit routes
b55b1aa (tag: 1.0.13) Version Bump
8b80e11 Paginate the token logs
fbf3e88 (tag: 1.0.12) Version Bump
e8f1882 Fix eveseat/seat#115 by adding new endpoints for role management
729971f Convert from a resource to controller route for roles
d2ff1df Merge pull request #1 from nizzan/patch-1
dc80447 Typo on API Token generation
d35e7ef (tag: 1.0.11) Version Bump
60475a4 Add /api/v1/corporation/assets-contents/{corp_id} endpoint
530703c Add missing PPHDoc comment for argument
3faff1e (tag: 1.0.10) Version Bump
99871c9 Rename repository method that was incorrectly called
131a3b8 Add /api/v1/corporation/all endpoint
be8e6aa Include key info and characters.
22f8b34 (tag: 1.0.9) Version Bump
f6bfc7e Update copyright
7f24bf8 Code style fixes
2409d0c (tag: 1.0.8) Version Bump
ad8351a Add Corp Pocos Endpoint
6ca59b0 (tag: 1.0.7) Version Bump
603cb76 Add ability to get a specific starbases info
a949267 (tag: 1.0.6) Version Bump
8f5c35f Allow for API Keys to be transferred to a different User
c712823 Add starbase and assets-by-location endpoints
220b7bb (tag: 1.0.5) Version Bump
86c4602 Specify versions with ~
3b80952 (tag: 1.0.4) Version Bump
55269b9 Add char & corp Bookmarks endpoints
b65799f Add Character Channels endpoint
dee0f28 (tag: 1.0.3) Version Bump
76647e9 Add localization support
de62767 (tag: 1.0.2) Update README.md
cc4ea85 (tag: 1.0.1) Version Bump
16c3896 Dont use a sub-menu
88348cb Cleanup Middleware and add Request Path logging
03064d4 (tag: 1.0.0) Add admin views, complete middleware and add menu.
c11ca2e Add Corporation API Endpoints
122f2da Add Character API Endpoints
dda7cbb Add endpoint to validate credentials
014502b Add roles and permissions query endpoint
4e88616 Add endpoints to get Role information
4516aaa Add CRUD for User management
2d129ea Update links to eveseat/api
2c2cef3 Fix typo
5620aa2 Update README
6905c26 Compelte the EVE API Key API
32d17cf First preperations for the SeAT API
57f8c6d first commit