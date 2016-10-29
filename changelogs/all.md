171a650 (HEAD -> master, origin/master) Re-enable the ApiServiceProvider
6791c38 Add flag to log queries to the log file
2b9ade7 Disable `ONLY_FULL_GROUP_BY` constraint
0eea8f0 Import Exception class
21ab024 Update readme.md
148a6b9 Upgrade to Laravel 5.3
2940be7 Merge pull request #133 from warlof/config
0c9b5b1 set log as daily log by default in order to make smaller file and help to track issues by time
821ec7f Add screenshots
13738be Remove erroneous [
6fc7bfd Update README
eaf83a3 Fix markdown syntax
6872975 Add link to finding logs etc
27b2b48 (tag: 1.0.12) Update readme.md
b067bd3 Add configuration items for EVE SSO
3c8e6cc Add link to contact info for general enquiries.
bfde328 Update ISSUE_TEMPLATE to be cleaner
c41637c (tag: 1.0.11) Fix eveseat/seat#80 by updating with upstream Laravel & Composer changes
f8ee744 Add docs badge
75ab31e Add ISSUE_TEMPLATE
f50c26f (tag: 1.0.10) Give Redis a day before moving form `reserved` to `main`
45b491f (tag: 1.0.9) Add comment block to help placing package service providers
9c5bcd6 Default to Redis cache driver
0a91d38 (tag: 1.0.8) Bump PHP version requirement due to PHP Late Static Binding Bug
82e486c (tag: 1.0.7) Default to redis Queue driver
35acb28 Ship with debug mode disabled
45c31c1 (tag: 1.0.6) Include pheal cache dir
3eb6883 Update favico
15c2a70 Update readme.md
018dc9d (tag: 1.0.5) Ensure the sde storage directory is available
496a73f (tag: 1.0.4) Fix #2
782f543 (tag: 1.0.3) Update readme
29f1993 Add notifications
a712bfc Set a default from
e53e723 Load command schedules from the DB
67fa32b Remove the hardcoded seeder
650c7de (tag: 1.0.2) Update readme
8b158d4 Add API repo
d854c33 Exclude auth from Csrf checks
4c0ea1e Bypass Csrf checks for API calls
f646309 Bootstrap the SeAT API Service Provider
ab10f46 (tag: 1.0.1) Update with minimum stability
cb617ba (tag: 1.0.0) Set dependencies to 1.* versions
822fbc1 (tag: 1.0-pre-alpha) Add the Notification Seeder
e412f6c Set default queue driver
c14940e Set session cookie name
ca43fc5 Redirect home to start SeAT Web UI
be3fac7 Override to allow requests
5071eb8 ADD README
f559e3e Set password reset email view
523f4cb Include eveseat/web dependency
364c57a Update config to make use of the Use model in eveseat/web
6af6aac Add friendly error messages
6d4bb73 Apply framework changes for Laravel 5.1.11+
dd81d71 Add new dependencies
24da1b1 Add new service providers
3d3c649 Prepare for packagist publish
5976bf9 Add Console and API Updater packages as dependencies
973b6d5 Add Map Updater Schedule
7fcf178 Schedule eve:update-eve daily
a56d3ad Schedule the eve:update-server-status command
c2812cf Set a few defaults
c0bf82e Remove unused command
58ff3c6 Remove composer.lock
aea4c7c Rename back to artisan
9806f4a Update gitignore
5658a92 Revert to App namespace
3424caf Ignore packages/
c8a5b6e Move namespace from App -> Seat
57487e8 Update .gitignore
644f3a9 Add license and update .gitignore
0bba931 first commit
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
cebd0ef (HEAD -> master, origin/master) Update to match new class names in eveapi repo
e1a95e9 Correctly identify the current user running the command.
e83fb0e Use `dispatch()` helper instead of Trait
953d790 Update PHP, Laravel & Guzzle dependencies
950768a (tag: 1.0.17) Version bump
5b6c15c Escape any special characters a password.
ffc04bf Code style and language fixes
bf32149 Merge pull request #1 from warlof/master
5c7f85b (origin/pr/1, pr/1) add a control for SDE version in order to avoid downloading it again allow the user to force an SDE re-installation using --force argument
c356fd3 (tag: 1.0.16) Version Bump
ebbebf2 Default to 6 hours to reap jobs
40707ef Add missing trait
43fc0b2 (tag: 1.0.15) Version Bump
a1da1a0 Remove string concatenation causing systax errors
57132cf (tag: 1.0.14) Version Bump
8c9abec Fix eveseat/seat#127 by removing string concatenation in Class property
974cfad (tag: 1.0.13) Version Bump
f3f44dc Add analytics hit information.
161cdee Add ClearExpired command
a87e8d0 Add `seat:queue:clear-expired` command.
a6e5e54 (tag: 1.0.12) Version Bump
0c9f1c7 Add a console command to set the admin email address
53fda6e (tag: 1.0.11) Version Bump
bb9841c Fix eveseat/seat#83 by ensuring seat:admin:reset recovers admin roles
8fb5ad1 (tag: 1.0.10) Version Bump
3e1dca5 Update copyright
d4b2b6f Code style fix
68e5638 (tag: 1.0.9) Version Bump
8b3aef9 Use `class` notation
6a6d779 (tag: 1.0.8) Version Bump
643479f Update diagnose with some more useful debug info
0132b4e Add Github version lookup
18bf548 (tag: 1.0.7) Version Bump
8934a36 Specify versions with ~
3f541b4 (tag: 1.0.6) Version Bump
a49d908 Revert b7cac27ebe4a1de8
7e1d13d (tag: 1.0.5) Version Bump
b7cac27 Drop guzzle version to match that of phealng
91f2e03 Cleanups
6361651 Add diagnose command
123bc36 Update README.md
338a397 (tag: 1.0.4) Cleanup outputs and sink to a filehandler instead.
0f83a18 (tag: 1.0.3) Version Bump
d0f6d31 Display versions in a table
3d472d4 Add notifications version
65f650d (tag: 1.0.2) Versino Bump
2a2a350 (tag: 1.0.1) Add web and api versions
8cc907d (tag: 1.0.0) Update required eveseat package versions
81fde9f Version Bump
fe0da9e (tag: 1.0-pre-alpha) Update README
05e59b3 Add a cache clearing command
41081d9 Add the UpdateSDE command
9af76fb use ::class format
7e0bae5 Add seat:admin:reset command
9f4e15f Update to match eveseat/eveapi model refacto
ee48a61 Add services version lookup
5d7ca5f Add a 'live' status command
bcd1feb Add command to update a single key
ee43dc5 Add seat:keys:show command
f72ba13 Style fix
b4bcc04 Add the console.config and update version command
8fe529d Refactor updater commands to the Eve\ namespace
cc92c10 Ensure only enabled keys are queued for updates
8f93faf Update to new eveapi version information location
fa5513d Queue Jobs using the UpdatePublic Job
887b89c Update readme with badges
74f82f5 Prepare for packagist publish.
a782121 Add the command to queue updates for API keys
14edaa8 Make all commands honor the Job Container
12538ef Add command for the Api CallList update
31e0d06 Add EVE Map Update command
20aa008 Add eve:update-eve command
b9b7545 Add the EveUpdateServerStatus command
c978b94 Add the add:job command for testing
c01ddd9 Start the Console package
f42ac27 first commit
34ac286 (HEAD -> master, origin/master, origin/HEAD) Extract some error handling up to the base abstract class
77172ec Cleanup methods, add type hints and remove unused code
f4af243 Make the integer migration a little more understandable.
66c6bba Add more contact related fields to the integer fixes
c083f61 Start refactoring the job tracking and error handling from a Trait to Class
61af28c Add migration to fix text sizes
946ee47 Fix labelMask integer sizes.
8699992 fix migration by disabling sql modes (#7)
bcd15e0 Fix for RefTypesModel->refTypeName not updating properly. (#8)
dffd1c9 Pass the the exception thrown into the `failed()` method.
e07f36b Fix schemas to work with MySQL in strict mode.
58da2c8 Require PHP7 and Laravel 5.3
8071dce Set the primary key type
91e4b2a Fix Jobs and dispatcher to accommodate L5.3 changes
e908f11 Rename `lists()` to `pluck()`
27bc174 (tag: 1.0.18) Version Bump
ca27d33 Fix imports, comments and codestyle
df05261 CharacterInfo API access mask compatability and legacy deprecation (#6)
4123994 Add missing comment
d33d2cf Merge pull request #5 from warlof/paid-until
ddf666f (origin/pr/5, pr/5) adding api_key_status into apiKey relation
d9af10e (tag: 1.0.17) Version Bump
1267346 Remove DispatchesJobs trait and use Bus Facade
804bbdc (tag: 1.0.16) Version Bump
cfdf20c Report Exception types that have occured.
69de2a2 Add timestamp to error.
87efa4b Add model for the failed_jobs table
c02f338 (tag: 1.0.15) Version Bump
3356cd0 Fix method comment
bd3e928 Handle the `failed()` method on jobs by updating the `JobTracking`.
c812028 (tag: 1.0.14) Version Bump
55f1ade Fix eveseat/seat#100 by finding by primary key only.
4451000 Fix eveseat/seat#99 by cleaning up after a key is deleted
8f8e0b1 (tag: 1.0.13) Version Bump
e9db18e Add a block if an admin contact email has not been set.
459d353 Add the new char/Clones and char/Skills endpoints as updaters
ccc7a08 Fix XSD as 2 new endpoints have been added, bumping accessMask to long type
85b21b0 Disable keys that respond with HTTP 403 in APIKeyInfo
56c8444 (tag: 1.0.12) Version Bump
00d8697 Catch the PhealException to handle XML parsing issues
ab00f40 Temporarily fix eveseat/seat#71 by catching the PhealException
20f00e9 Mark jobs as done in the case of errors.
ab985bd (tag: 1.0.11) Version Bump
d4d4f50 Dont disable on HTTP 403. Too many false positives.
3a5c6cf (tag: 1.0.10) Version Bump
6995d17 Fix eveseat/seat#52 by searching by refTypeID to update
ab271fa (tag: 1.0.9) Version Bump
c285f7d Update copyright
e741457 Code style fixes
eac8500 (tag: 1.0.8) Version Bump
83cb845 Fix eveseat/seat#37
f816c1d (tag: 1.0.7) Version Bump
dd72510 Default to an Unknown system
1e41a94 Default to the solarsystemid instead of null
da049c7 Fix eveseat/seat#8 by checking if the body exists before insert
ff48a73 Add the CustomsOfficeLocations API updater
601eb36 Specify phealng version with a ~
a08e970 Remove specific minor version.
a93f674 Bump minimum PHP version
74dcedb (tag: 1.0.6) Version Bump
fb2e473 Set composer versions using ~
f9fdfb5 Merge pull request #4 from warlof/shareholders
fd53795 Keep track of the closest distance.
9840802 (origin/pr/4) Provide a fix to eveseat/seat issue #21
69e8c3b Merge pull request #3 from warlof/contactslabels
173f57c (origin/pr/3) Provide a fix to eveseat/seat issue #5
03101f9 (tag: 1.0.5) Version Bump
5562f03 Add corporation bookmarks updater
17c7c41 Resolve the closest celestials for bookmarks
c7bef60 Only resolve to items that have names
856f66f Add channel relations
7be3801 (tag: 1.0.4) Version Bump
6302a17 Handle some HTTP response codes for expired keys
53c168f (tag: 1.0.3) Add check to job_ids and version bump
dc612d9 (tag: 1.0.2) Version Bump
a8bcd62 Compile a sane user agent for eveapi xml requests
6eced6a Change - to _
05378b6 Catch the ConnectionException when checking keys
fa6bcf6 Decrement the counters when checking key types
78441a9 Dont increment past the limit
ff3df0a Add ability to check if the EVE XMLAPI is down.
3ec7598 Add primary key
f954257 Add primary key.
f4d133a (tag: 1.0.1) Version Bump
6db0044 Update to Pheal2.3 and use the Guzzle fetcher
4354a90 Reload the info relationship on a key to update accessMask
47ddd2b Update README.md
a49216a (tag: 1.0.0) Version Bump
debc408 (tag: 1.0-pre-alpha) Update README
3ab3bb9 Populate $fillable properties to include corpIDs
7577325 Small refactor to reduce code duplication
403b894 Add method to get a corporationID
f116fbe Fix up testing by allowing the access bit to be set in the constructor
18e3967 Actually set the configured instance
18522f4 Load access definitions directly from the config
d9c3d8f Resolve PhealNG out of the IoC
3e75254 Increase field size
cc1823d Add User relationship
2c3f4a6 Change Case
411e46c Refactor Models into categorized namespaces
0940ea9 Make Jobs aware of the Pheal\ConnectionException
acf0a53 Write a log entry if the JobTracker lookup failed
bc9b4ce Dont try and get Courier contracts items
10f496a Dont type hint the exception type, as any exception should get here.
d1d8555 Cater for the strange AccountStatus call access.
318de50 Rate Limit requests p/s to remain under 30 p/s
dfcd9c6 Jobs can now be assigned to a queue for priority.
5b8cd0b Prevent an array_merge() attempt on NULL
31f1af0 Allow for granular update worker control
ca9ff3e Collapse KillMail Attacker, Detail and Items tables.
16e75b5 Split configs up and update the Service Provider
1639d2b Move load_workers to the JobTracker Trait
827f34a Small refactor to remove duplicate code starting workers.
66bb167 Code Style fixes
9701167 Log failed jobs to the general log.
5c76f57 Fix Line Seperator to LF
e9eb32d Add sample XML
2712ac3 Remove unnecessary leading \
acd5c1b Add Corporation WalletTransaction Update worker
42e8355 Add more transaction uniqueness
b4b5c01 Add missing accountKey arg
c27e7d3 Add Corporation Wallet Journal Update worker
fa876b7 Add primary key for updates
0117329 Add Corporation Titles Update worker
30162a2 Add StarbaseList and Detail Update workers
821b63b Add Corporation Standing Update worker
ccfa8b6 Add Corporation Shareholders Update worker
6478410 Add Corporation MemberSecurityLog Update worker
84cabb4 Add Corporation MemberTracking Update worker
f860322 Only set titles if the API response had some
eac6568 Add Corporation MemberSecurity Update Worker
92cb2a0 Add Corporation MemberMedals Update worker
adb06db Add Corporation Medals Update worker
799246d Add Corporation Market Order Update worker
91b9b8f Add Corporation KillMail Update worker
422cc28 Add Corporation IndustryJobs Update worker
a8c58c5 Add Corporation Customs Offices Update worker
2bfb7cc Add Corporation Sheet Update worker
e91a78f Add Corporation Contract/Items Update worker
c8ba721 Add Corporation ContactList update worker
8042cb9 Update comment
9876ed2 Add Corporation Locations Update worker
4949d96 Add method to find celestials closest to an x,y,z
d7f3844 Add the Corporation Assets Update worker
367d83d Add Corporation Account Balance worker
85b7ed4 Slightly increase possible value
a02f4f6 Add helper to determine corpID for corp keys
942ee79 Get a fresh instance of the model as it just updated
aaa4e2b Use relation to get type instead of a new query
0cef16e Code Style Fixes
3127104 Optimize a few updater workers, fix comments and styling
ed350b6 Check if api_info is available first.
3aabc11 Add EVEAPI error handling
e38f15a Check if the info relation exists before using
eda56f2 Add test for accessMask checking
efa6bd3 Implement CanCheck to check API key accessmasks
076a608 Improve readability of error output
c327e62 Bump dependencies to stable versions only
d3690c0 Update class comments
d377c46 Move list of update classes to a config file
55c3d31 Fixup tests since the phealng optimization
d0f93b4 Optimize PhealNG usage.
6a0182e Add Bookmarks Update worker
5cc2f16 Update Badges
72f4a40 Update License
62abf5d Add Chat Channels Update worker
b1c1890 Fix reference to transactions element
9d17c5e Add Utils test
effef96 Update License
55a0f70 Use 'hash' as primary key
9a3a1e3 Add Wallet Transactions Update worker
8149688 Add the Wallet Journal update worker
7fb983f Add Calendar Events Update worker
fc553d5 Add Standings Update worker
b06989c Add SkillQueue Update worker
faf93b0 Add SkillInTraining Update worker
4ca03ab Add Character Research Update worker
532b75b Add Character Market Orders update worker
4d2baeb Add Planetary Related Update workers
9f82357 Add Character Notification Update workers
985ec34 Add character mailing lists update worker
9a1da2f Add MailMessage Update worker
fdddcec Increase size of output column
81bfd5e Add supporting files for Char KillMail Updater
ea775fd Add Character KillMail Update worker
53b3b92 Add CharacterInfo Update worker
259f2c6 Add Industry Update worker
4cb4c79 Fix a few small keying issues
75718fe Add Contract and ContractItems update workers
bb8fdbd Add Contact Notifications update worker
ae67622 Add ContactList update worker
576e022 Add complete CharacterUpdate worker
77ed8ca Bump default cURL timeout to 60s
6d15331 Fix issue causing member corp allianceID to be 0
08ef47a Add the Character AssetsList Updater
0a0f959 Add AccountBalance Update worker
5a65242 Fix up the relationship keys
b12f246 Add a relationship between API Keys and Characters
f20b464 Prevent an errored job from being marked as Done
13ed536 Add AccountStatus sample XML
b26fcf2 Add AccountStatus Updater
93952a3 Update Checker to queue jobs based on key type
c61dd09 Style and docblock fixes
db60993 Abstract some of the repeated Trait usage
7124c77 Constrain the character removals to the key
b5f2f61 Remove unused PhealException
b0063c7 Start the Key pickup worker
3e97b6c Return the object when setting the key/vcode
99081b7 Group API Tests to be easily excluded by PHPUnit
207a33d Add the Job Container to resolve Job information
598ed88 Remove unused DispatchesJobs trait
93eec75 Add the API CallList Updater and Test
79f4a16 Add Code Climate
f881d47 Update README
aafe40f Update travis-ci to include newer PHP and HHVM
d21e557 Add Travis-CI config
3da6a8e Add tests for the currently implemented calls
21a3f2d CS Fixes
82c0f51 Add Test to validate ServerStatus API Response
1ee3bb0 Small namespace change for the test
21be320 Start Testing! :)
6d0ed85 Throw an exception if an api key is empty
52ad9b7 Add Map Jumps Update worker
6c4bc86 Add Map Kills update worker
4720ae1 Fix job to actually update if something changes too
6d39cb2 Update Models defining new primary keys
377428b Modify Migration Indexes
c753ad1 Add Map Sovereignty Update workers
187b336 Add AllianceList update
8fff877 Add ConquerableStationList updater
a75c66e Add eve/errorlist API call
b02dc11 Add Eve RefTypes API Call
9c61de8 Move Jobs error handling to a trait
8bc8a64 Implement the Job Tracker
0d0ab93 Add a job manager
ca0a6d7 Add generated docblocks
086ebb5 Complete ServerStatus Update
8991564 Start core logic and add server status checker
b6991b9 Start a few things to test job workers
40d4948 Start composer package
af4f12f first commit
6caa863 (HEAD -> master, origin/master) Update PHP & Laravel dependencies. Remove psr/log dependency.
624e13c Apply new global web middleware
c115945 (tag: 1.0.4) Version Bump
7b0cd6f Update copyright
23e89b1 Code style fix
d47b267 (tag: 1.0.3) Version Bump
e0a5b53 Specify Versions with ~
aedd78a (tag: 1.0.2) Version Bump
a2e7ddf Add suport for lacalization
6594754 (tag: 1.0.1) Version Bump
ccf7596 Update README.md
70994aa Add more complete message
15b1175 (tag: 1.0.0) Add views to see notifications
fd76941 Fix typo
a5f93e7 Update README
c22a837 First iteration of the notification package
032bebf first commit
d13d650 (HEAD -> master, origin/master, origin/HEAD) Refactor Corporation repo to use structured classes
ab9f039 Refactor the Character repository to use seperate classes
3f7a1f9 Return a single value instead of array
6b0aa6c Remove usage of `collect()`. Collections are returned by default
7784321 Update PHP & Laravel dependencies
1de059b Log queries based on the value of `DB_DEBUG`
c5ac762 Revert groupBy changes introduced in 982b8661
ee0ff98 Upgrade to coduo/php-humanizer 2.0
869f330 Fix namespace change for humanizer 2.0
982b866 Fix strict mode groupBy constraints
3f1f2c5 Make the query debugger listen on the DB facade directly.
0ff8a45 Fix Job to match L5.3 changes
ac59839 Rename lists() to pluck()
5dc3ac7 Get the value with `value()` instead of `pluck()`
49bc082 (tag: 1.0.23) Version Bump
a199fa9 Add getCharacterAlliances method
dfaa83a Add char and corp minimum mask defaults
4739b90 Add a default for the `installed_sde` setting
a0a0c75 (tag: 1.0.22) Version Bump
02ad71e Seed the expired job time to run every 6 hours
0ad3ccf (tag: 1.0.21) Version Bump
cfcefda (tag: 1.0.20) Version Bump
7fa3040 Add missing import of CharacterSheetCorporationTitles
b4a8080 Set available options and defaults for usage tracking
b2765c6 Add analytics Jobs using Google Analytics measurement protocol.
9d23cb6 * Add corporation titles to character sheet (#7)
26c1673 Fix eveseat/seat#112 by using an advanced where to group the filter
58cfc96 Add the `seat:queue:clear-expired` scheduled command
b2b9995 (tag: 1.0.19) Version Bump
744e982 Paginate Killmails
5711563 Paginate contracts. Part of the fix for eveseat/seat#111
b3d538d (tag: 1.0.18) Version Bump
305a3ab Sort killmails by newest first.
2edf0fd Add module info if a single starbases' info is called
e35f552 (tag: 1.0.17) Version Bump
10c4a86 Set default values for 'allow_sso'
439fbac (tag: 1.0.16) Version Bump
ea240c7 Add defaults for minimum access mask checking settings
d7b7eaf Add the search service
ce085f7 Fix eveseat/seat#93 by filtering corporation_account_balances too
0c03b8e Modify timeline method to retrive one specific message
570bbd0 (tag: 1.0.15) Version Bump
630b8af Remove unused pagination and CS fixes
cbc4206 Services for Corporation Ledger queries. (#5)
b87d364 Order jobs by creation date
e4d521b (tag: 1.0.14) Version Bump
96c9fb5 Update copyright
c9cd51c Ensure that people.view role is enforced
2f1e9e3 Add methods for People groups
f7bb649 Handle some unicode characters for cases like eveseat/seat#13
0ad1ffa Code style fix
e33ed92 (tag: 1.0.13) Version Bump
582d719 Fix eveseat/seat#28
c3d9aaf (tag: 1.0.12) Version Bump
bee194f Add method to get corporation customs offices
bb1cd45 (tag: 1.0.11) Version Bump
0d139b2 Allow starbase details to be loaded by starbase_id
e985e13 (tag: 1.0.10) Version Bump
9e75900 Revert version setting via ~
cd3878c (tag: 1.0.9) Version Bump
a0c30a9 Version Set via ^
ebd21c7 (tag: 1.0.8) Version Bump
e7a055d Set composer versions using ~
08a50d8 Determine capacity bonus with tower
aa51300 Temporarily ignore nested groups
5ff8e0a Add methods to get starbase related data
63e9be9 Return paginated results
5734db7 (tag: 1.0.7) Version Bump
e221f72 Add method to get corp bookmarks
30699d3 Add method to get character bookmarks
afd7cba Add method to get character chat channels
6ca677b Second attempt at fixing eveseat/seat#7
aa17e7d (tag: 1.0.6) Version Bump
691dc5c Prevent dupe or corp chars from showing
1b93322 Prevent duplicate entries in corp member tracking
af4abdc (tag: 1.0.5) Version Bump
cda2f34 Default to english language
ea02832 Add method to get mail timeline
28b0933 Suppress errors incase the html is invalid
012e0e6 Add method to get an email for a character
d087604 (tag: 1.0.4) Version Bump
d3d6bd0 Add an admin contact setting
a5b4135 Order jobs by date
e1c75bb (tag: 1.0.3) Version Bump
717f9fb (tag: 1.0.2) Add server status method
f2172dc Update README.md
8b65137 Add default MFA setting
f32b199 (tag: 1.0.1) Version Bump
9a2fe0f Allow to get/set settings for another user by id
71504e9 Add default for email notifications
8109b5c Add service for database stored schedules
d4afc21 Ensure we pass integers to the helper
300cdde (tag: 1.0.0) Update required eveseat package version
526493c Style Fixes and Version Bump
9ded93d Add registration options
e5348f0 Update to support new settings features
f601b60 Move options scope to public
dcbd238 Add a setting() helper and provide some defaults
82115c2 Add a settings service
c72cd8a Add methods to query corp security info
5371848 Add method to get corp member tracking
93958d6 (tag: 1.0-pre-alpha) Update README
666036a Add method to get corp wallet transactions
bcb36f7 Fix filter rule reference
5e579ec Add methods to get standings and wallet journal
91163b3 Fix a join
bab5d59 Add method to get corp market orders
6b2734d Add method to get corp killmails
513c1e5 Add method to get corp industry jobs
eb0b9d7 Add method to get corp contracts
3b2e7eb Add methods to get corp contacts & labels
057e1d4 Add method to get corp assets
907870a Add methods for corp summary pages
c4a4977 Small refactor to remove attributes instead of making them blank
0b1ee7a Add method to cleanup CCP produced HTML
11e55c6 Add method to list corporations
3a76e64 Fix typo
02eea36 Add ability to just dump query and continue load
c71ca03 Add method to get character standings
be1c6db Add method to get character research info
7d0105c Add method to get character pi
6ea00fb Add methods to get character market orders
18e3580 Add method comments
4daabd8 Add method to get character industry
196e968 Add method to get contract information
3ad8de1 Add method to get killmails
2c5ca99 Lock type image to max 32/64px
0071fa7 Add character contact lists and calendar repositories
11ebe15 Add character notifications repo
52807cf Add the Notification Types Seeder
6560b34 Add rules to ensure columns can not be tampered with
bb32b1b Add Character Assets services
cc493be Style fixes
0e56275 Add Mail Service for Characters
6fa7631 Add Character Wallet Transactions Service
bd1b364 Add Wallet Journal Services
22d7e6f Add option to auto-detect image types
f899060 Rename method from Character->Eve
d3f6fb7 Add more methods for character information
46910d1 Fix a table ambiguity problem for characterID
33463b9 Add more repository methods
f75cd7c Add Services for Character Skills
d35099a Add security repository
9bcb126 Add more methods for character info
71e3864 Add a number formatter
55a29d2 Add repositories to get character information
04df3b9 Add a query builder filterable helper
0fdea02 Add SQL debug helper
6e32c77 Add Respository to support the Queue
54cda05 Set extention correctly based on image type
4172206 Add a service to prepare lazy loaded <img> tags
89dfbb2 Add user modifiction services
30bdace Add repositories used in eveseat/web acl
a8ff125 Update to match eveseat/eveapi Model refactor
4a69ce0 Add Config file
ea84fb0 Add Queue Data Source
2f60e1d Add EveApiKeyData service
467fb42 Update badges
5779eff Prepare repository for packagist
a46f437 Initial commit
2d73c70 (HEAD -> master, origin/master, origin/HEAD) Update to match new class names in eveapi repo
249c5af Fix language string
038ba4d Update to make use of new Corp repository classes
fb129f9 Update to make use of new Character repository classes
799fdee Update distrib JS/CSS
74752d2 Upgrade to AdminLTE 2.3.7
735279c Remove usages of `collect()`. All queries return a collection by default
ee461fb Upgrade `pragmarx/google2fa` & `league/csv` dependencies
e414ecb Updpate Form Request validation to extend new base class
fe0606d Show icon of actual ship instead of a generic one
e4821ca fix paid-until issue in detail api key view due to possible missing status (#40)
2bef52c Move logout to a POST method as the new Laravel default
abea1b1 Rename `lists()` to `pluck()`
c215f78 Update Authentication Scaffolding for Laravel 5.3
97fdc4d Add Notifiable trait introduced in L5.3
6366ccc Update Events to use new Class based events for L5.3
c45ac15 Update composer to require PHP7 and Laravel 5.3
9fdea41 (tag: 1.0.31) Version Bump
8d1f8fd Formatting and style fixes
360e76c add SDE version into both footer and settings page (#39)
1db0265 Add alliance name filter to character list
770044c Fix permission issues (#38)
7c935df add alliance icon and name into character list. fixes eveseat/seat#134
2ad376f Rename EveonlineProvider.php to EveOnlineProvider.php (#36)
edb6543 Fix formatting
584c9e6 Add collateral amount into contract list (#33)
433f10a Fix formatting and restore min_access_mask language string
60b7cd6 Create a new minimum required mask dedicated for corporation (#34)
22c4209 Add paid-until in Key Details view (depends on PR paid-until branch from eveseat/eveapi) (#32)
bc1f5ac (tag: 1.0.30) Version Bump
33b0e03 Update full api mask (#31)
ec19039 Add link to analytics doc
ccd332d Add ability to disable tracking completely.
c7372e9 Add corporation titles to character sheet
b527652 Add contact tracking links into character and corporation contact list (#30)
bc76609 (tag: 1.0.29) Version Bump
12a1229 Resolve names of affiliations.
e1c82e3 Paginate character contracts and all killmails
91a5e98 Fix eveseat/seat#111 by paginating the results
3ac3699 Fix eveseat/seat#121 by adding a button to re-enable all keys
a6a8897 Add warning about a autogenerated email from sso
c66c68e Fix spacing
4aa702d Small codestyle related fixes
1cca04d Provide a way for user to change their email address (#27)
e27d545 Adjusted setting (#26)
4e5225e (tag: 1.0.28) Version Bump
5b2443b FIx indentation
f9b6ee8 Added total values to the Bounty Prizes and PI monthly ledgers. (#25)
21fc0d9 Remove logic that is now in the service repository.
7689032 (tag: 1.0.27) Version Bump
c036c44 Update Provider with new method name.
981ccc4 (tag: 1.0.26) Version Bump
0796b2c Allow SSO to be enabled/disabled via the web interface.
7a605be Give accounts a temp email address and flag Sso created accounts
6efc9bf Add first support for the EVE Online SSO
168bb3e (tag: 1.0.25) Version Bump
aee17af Add ability to force a minimum API access mask.
5101767 Start adding search functionality
b8ac4fb Remove accountid as it is not useful data
8604036 Fix eveseat/seat#81 by validating for numeric instead of integers
e1cd641 Fix eveseat/seat#78 by adding a link to view one mail only
60727e4 Warn if the default admin contact is still set. Ref eveseat/seat#77
a5d1f8f Fix eveseat/seat#65 by setting the key_id in the model
9884772 fix reinforcement time using API stateTimeStamp (#24)
c20194b (tag: 1.0.24) Version Bump
eac101f CS Fixes
f6e3186 Small refactoring and CS fixes
9997914 Adding Corporation Wallet Ledger (#23)
954c178 (tag: 1.0.23) Version Bump
498b868 Fix eveseat/seat#70 by ignoring the current users email in the constraint
8422602 Fix eveseat/seat#57 by adding missing language strings
cc8019a (tag: 1.0.22) Version Bump
0f02f88 Fix eveseat/seat#59 by adding a unique validation constraint
c69fa2f Add button to easily re-enable keys
70783d8 (tag: 1.0.21) Version Bump
c9188b7 Fix eveseat/seat#60 by using `firstOrNew` instead of create
98b9679 Fix eveseat/seat#51 by always showing the pagination
e2056a1 (tag: 1.0.20) Version Bump
92986b7 Remove pcntl requirement
ad5f515 Merge pull request #21 from warlof/french
642a832 (origin/pr/21) New french translation according to 1.0.19
f212c78 (tag: 1.0.19) Version Bump
d5376f9 Update Copyright
39c8243 Subclass the bouncers
afb0be5 Add a People Groups feature
17c4f3e Set queue status update time via configuration
5d30ff0 Fix eveseat/seat#48 by adding data-order attributes
530c268 Add a check for loaded modules and php version
c84baaa Merge pull request #18 from warlof/ticket38
e4e1fd0 Merge pull request #20 from warlof/ticket43
94e470d (origin/pr/18) Fix wishlist #38 eveseat/seat#38
21a3bb3 (origin/pr/20) Fix issue eveseat/seat issues#43 - Update calc formula - Adding ceil in order to get round item unit (ccp like)
274409b Use league/csv to parse CSV's instead of the homebrew
741755d Remove unnecessary re-fetch of model data
b7ff1a2 Fix eveseat/seat#39 by changing ownership of an existing key.
8fcc13e Remove footer. Datatables will count the keys
b357826 Code formatting fixes
d5f58de Merge pull request #19 from Cynabal/master
7a78e2f Merge pull request #17 from warlof/french
9d2ab0f (origin/pr/19) Update seat.php
86da25f (origin/pr/17) New translation according to v1.0.18
69239bf (tag: 1.0.18) Version Bump
33470ce Allow packages to hook into corporation menus
24c9f1d Only attempt to read package menus if they are defined
3b7ecad Allow packages to hook into character menus
bac4a6e Add Datatables to starbase summary
ec9d5c8 (tag: 1.0.17) Version Bump
aaaac36 Fix eveseat/seat#29
6de7e1e Add Datatables for tables.
075784c (tag: 1.0.16) Version Bump
b688c4f Add planet type icons
54ccdec Add corporation Pocos view
bbede7b (tag: 1.0.15) Version Bump
63f308a Load starbase modules via Ajax calls
c0f48df Display page render time
3f8587c (tag: 1.0.14) Version Bump
14d87b4 Merge pull request #13 from warlof/ticket5
d412b7e Excluse Towers themselves from module views
98a8e19 Use a macro for progressbar generation
c0e9ce3 Remove unused variables
22932b4 Refactor Starbase views mostly for performance reasons
0cefaac (origin/pr/13) fix issue #5 about labels display on neutral and negative standing
936e8b8 (tag: 1.0.13) Fix a assets check, add missing string and Version Bump
7bdbf10 (tag: 1.0.12) Version Bump
6c365ad Specify versions with ~
3f604e2 Merge pull request #11 from warlof/french
c1f4657 (origin/pr/11) add new translations according to recent commits (for 1.0.12)
ed485b3 Move strontium usage to its own string for easier translation
64a6f86 Take into account bonusses silo/coupling array capacities
488fd3b Merge pull request #8 from warlof/unknown-item
cd66a8a Add Starbase details views
f9dc521 (origin/pr/8) fix issue #9
9f74d1c Add more details about starbases
7e67371 First pass at adding starbase views
9496188 Merge pull request #6 from warlof/french
2491e69 (origin/pr/6) Translate SeAT in french according to 1.0.11
f5fa4e3 Show timestampts and paginate wallet info
c6b4311 Fix eveseat/seat#15
ca67d0a (tag: 1.0.11) Version Bump
78da260 Add ability to view corporation bookmarks
eda1260 Add ability to view character bookmarks
8e1285e Add ability to view character channels
5aebf1e (tag: 1.0.10) Allow French to be chosen and Version Bump
dae1719 Merge pull request #5 from warlof/french
6e827ae (origin/pr/5) Translate SeAT in french according to 1.0.9
9e4cd79 (tag: 1.0.9) Add account info check and Version Bump
bfaabe2 Merge pull request #4 from freedenizen/master
d802b98 (origin/pr/4) add updated_at timestamps to Character and Corporation Sheet summary
0ece0ce (tag: 1.0.8) Version Bump
616067c Check if we have data before attempting to display
99c14a3 Fix eveseat/seat#10
660b6fa (tag: 1.0.7) Version Bump
b65aa7e Remove URI scheme
639b3fb Add missing language definition for view
2042098 (tag: 1.0.6) Version Bump
83a7ea8 Add Afrikaans language support
0039045 Add ability to select a preferred language
30a71e6 Update langauge strings
2956a15 Resolve contract issuerID's to names
36ea925 Apply number() to a few values
40e5c24 Add ability to view profile login/logout history
a8e93d7 Add for user password resets
81682c4 Add recipient info into the mail timeline
cc141c8 Add id-to-name helper
6999007 Add X-CSRF Token for ajax calls
6915fec Add the mail timeline view
5ade565 Add ability to view character email
df6ddae (tag: 1.0.5) Version Bump
14bc397 Add ability to set an admin contact
5e6498b Add links to external services
f819124 Show output of jobs
070c232 Show eveapi errors status
80775e2 Allows superusers to transfer keys to other owners
4aab9b8 (tag: 1.0.4) Version Bump
bc8e6eb (tag: 1.0.3) Start something for a dashboard
0238e32 Update README.md
73d415d Add optional Google Two-Factor TOTP support.
84723ff Merge pull request #3 from Cynabal/patch-1
2d98ead (origin/pr/3) Update add.blade.php
7fcac57 (tag: 1.0.2) Version Bump
020c885 Add notifications version
f9fdaf6 Dont force packages to set a permission
5d1bb8c Add email notifications setting and new email templates
4bade0d Auto update copyright year
9eba303 Add WebUI to manage schedules
4598815 (tag: 1.0.1) Version Bump
2c683ba Dont force a package to have a sub-menu
6c13e32 Resolve menu routes in the sidebar view.
e8f3237 Add api version display
0f6d4ec First pass in allowing packages to add menu items
fe117ce Add hasRole() method
be056a9 Fix #2
e885f07 (tag: 1.0.0) Style fixes and version Bump
fddc5ba Add SeAT Settings Page with registration toggle
30b2b9c Add more settings options
bb6e8ed Add ability to change SeAT theme.
8dbb713 Read skin ccs filename from settings()
67d823c Read some values from settings
91872a1 Remove unused HTML and fix brand route
3ec66f3 Reduce icon size and add corp icons
e78c62f Add more complete corp security views
13f6c9d Add ability to view corp member tracking
6332cd7 (tag: 1.0-pre-alpha) Update README
a48340a Login using names instead of emails
2dfdc27 Add ability to view corp wallet transactions
06c4741 Add ability to view corp wallet journals
97547a7 Add ability to view corp standings
1a825e0 Add ability to view corp market orders
bab5d6a Add ability to view corp killmails
26923cc Add ability to view corporation industry jobs
fc43803 Add ability to view corporation contracts
a386881 Add ability to view corp contacts
110b142 Add ability to view corporation assets
2b9dd85 Add ability to view corp summary
0bf5bdc First work on corporation views.
5114d4f Resolve a trait method conflict
5eaffdc Add ability to mass import keys via CSV files
17feb08 Add ability to view character standings
797c9f0 Add ability to view character research info
771ee34 Add ability to view character PI
0fcb7de Add ability to view character market orders
a6b7ac6 Add ability to view character industry
c020c36 Small UI refactor to make it cleaner
0d5e18a Add character contract view
f36e34b Add ability to view character killmails
45e8dd5 Link to character details
08d1d48 Add character contacts view
dc3a396 Add character calendar view
085368f Add character notifications view
04ca0ee Add filter rules.
ccc5ad2 Add Character Assets View
c748d29 Add table-responsive
9aaa7ae Add Character Mail View
f046272 Add Character Wallet Transaction View
1ae69e0 Add Character Wallet Journal View
814a95d Rename method from EveRepository
5d9cfc1 Add Implants, Jump Fatigue and Clone info
ac83d39 Minor formatting changes
3631b89 Re-arrange character details layout
e23a153 Add more character sheet info and shuffle a few things around
c414bb2 Create a base view for character detail views
d3fc448 Add Character Skills view
51caf72 Add Security logging and viewing abilities
7debd56 Start the Character Viewer
5bfbed0 Small responsive fixes
4cf03ed Add All Characters View
51ccf46 Add hasAny()
12e05de Split permissions into categories
50a68ab Add a view into the Job Queue as well as some management
0da342b Add live queue status updates
b9df4c4 Fix cases where keys with missing info would throw errors
9faffab Remove usage of the Redirect Facade
2250508 Add ability to manually start a job update
3e34b3e Add key detail viewer and introduce the keybouncer
85bf567 Add ability ti list and delete API keys
2fe3d76 Add lazy image loading support
ee21c49 Style fixes
1de991a Add ability to add new Api Keys
358ba7f Make sidebar permissions aware
41190e6 Introduce the Bouncer and hes Clipboard 🚪
c2edc6b Use auth() helper instead of Auth Facade
2a864dc Fix some inconsistency with edit/updater user lang
e473bba Swap input for has to read better
5e65509 Allow for users to be quick added
89ca4e1 Allow for the account status to be filled
05e6019 Resize grid to match other configuration views
fdeb2cc Rename menu entry to match page title
7a03e34 Complete the impersonation feature
6195979 Add ability to delete users
0675ef9 Cleanup when a user is deleted
4c58659 Allow for users to be modified
a3f1882 Add a basic summary of user roles and affiliations
f03f872 Localize flash messages on perm/role changes
679b020 Fix typo in affiliation form request validator
2e656a8 First iteration of Acl methods and web structuring.
e8c4343 Highlight submenu items based on URL match
b6cd2b9 Have the sidebar honor the Locale
1f91ef0 Add view composer to build the sidebar menu
3425769 Add a User view composer
3e72326 Restructure Service Provider
4aa96f5 Fix duplicate 'reset' translation key
1160deb Use class property
22c7747 Add password reset functionality
9377f67 Add README
f16a71d Start web interface
3f15794 Initial commit