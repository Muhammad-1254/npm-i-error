# npm-i-error

0 verbose cli C:\Program Files\nodejs\node.exe C:\Program Files\nodejs\node_modules\npm\bin\npm-cli.js
1 info using npm@9.6.7
2 info using node@v18.17.1
3 timing npm:load:whichnode Completed in 3ms
4 timing config:load:defaults Completed in 4ms
5 timing config:load:file:C:\Program Files\nodejs\node_modules\npm\npmrc Completed in 2ms
6 timing config:load:builtin Completed in 3ms
7 timing config:load:cli Completed in 3ms
8 timing config:load:env Completed in 2ms
9 timing config:load:file:E:\extras\Work space\Upwork\Airbnb-clone-pablo-02\nextjs-airbnb-clone-starter\public\.npmrc Completed in 1ms
10 timing config:load:project Completed in 1ms
11 timing config:load:file:C:\Users\3TEE\.npmrc Completed in 0ms
12 timing config:load:user Completed in 0ms
13 timing config:load:file:E:\extras\Work space\Upwork\Airbnb-clone-pablo-02\nextjs-airbnb-clone-starter\public\etc\npmrc Completed in 0ms
14 timing config:load:global Completed in 0ms
15 timing config:load:setEnvs Completed in 2ms
16 timing config:load Completed in 17ms
17 timing npm:load:configload Completed in 17ms
18 timing npm:load:mkdirpcache Completed in 0ms
19 timing npm:load:mkdirplogs Completed in 0ms
20 verbose title npm i
21 verbose argv "i" "--prefix" "public"
22 timing npm:load:setTitle Completed in 2ms
23 timing config:load:flatten Completed in 4ms
24 timing npm:load:display Completed in 5ms
25 verbose logfile logs-max:10 dir:C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_37_13_539Z-
26 verbose logfile C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_37_13_539Z-debug-0.log
27 timing npm:load:logFile Completed in 25ms
28 timing npm:load:timers Completed in 0ms
29 timing npm:load:configScope Completed in 0ms
30 timing npm:load Completed in 53ms
31 timing arborist:ctor Completed in 1ms
32 silly logfile start cleaning logs, removing 18 files
33 timing idealTree:init Completed in 345ms
34 verbose shrinkwrap failed to load node_modules/.package-lock.json out of date, updated: node_modules
35 timing idealTree:userRequests Completed in 10ms
36 silly idealTree buildDeps
37 silly logfile error removing log file C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_37_06_530Z-debug-0.log [Error: EPERM: operation not permitted, lstat 'C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_37_06_530Z-debug-0.log'] {
37 silly logfile   errno: -4048,
37 silly logfile   code: 'EPERM',
37 silly logfile   syscall: 'lstat',
37 silly logfile   path: 'C:\\Users\\3TEE\\AppData\\Local\\npm-cache\\_logs\\2023-09-21T22_37_06_530Z-debug-0.log'
37 silly logfile }
38 silly placeDep ROOT airbnb-clone@1.0.0 OK for: public@0.1.0 want: file:..
39 timing idealTree:#root Completed in 13ms
40 timing idealTree:node_modules/airbnb-clone Completed in 0ms
41 timing idealTree:buildDeps Completed in 14ms
42 timing idealTree:fixDepFlags Completed in 5ms
43 timing idealTree Completed in 384ms
44 silly logfile error removing log file C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_37_02_901Z-debug-0.log [Error: EPERM: operation not permitted, lstat 'C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_37_02_901Z-debug-0.log'] {
44 silly logfile   errno: -4048,
44 silly logfile   code: 'EPERM',
44 silly logfile   syscall: 'lstat',
44 silly logfile   path: 'C:\\Users\\3TEE\\AppData\\Local\\npm-cache\\_logs\\2023-09-21T22_37_02_901Z-debug-0.log'
44 silly logfile }
45 silly logfile error removing log file C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_36_59_156Z-debug-0.log [Error: EPERM: operation not permitted, lstat 'C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_36_59_156Z-debug-0.log'] {
45 silly logfile   errno: -4048,
45 silly logfile   code: 'EPERM',
45 silly logfile   syscall: 'lstat',
45 silly logfile   path: 'C:\\Users\\3TEE\\AppData\\Local\\npm-cache\\_logs\\2023-09-21T22_36_59_156Z-debug-0.log'
45 silly logfile }
46 silly logfile error removing log file C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_36_55_629Z-debug-0.log [Error: EPERM: operation not permitted, lstat 'C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_36_55_629Z-debug-0.log'] {
46 silly logfile   errno: -4048,
46 silly logfile   code: 'EPERM',
46 silly logfile   syscall: 'lstat',
46 silly logfile   path: 'C:\\Users\\3TEE\\AppData\\Local\\npm-cache\\_logs\\2023-09-21T22_36_55_629Z-debug-0.log'
46 silly logfile }
47 silly logfile error removing log file C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_36_51_971Z-debug-0.log [Error: EPERM: operation not permitted, lstat 'C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_36_51_971Z-debug-0.log'] {
47 silly logfile   errno: -4048,
47 silly logfile   code: 'EPERM',
47 silly logfile   syscall: 'lstat',
47 silly logfile   path: 'C:\\Users\\3TEE\\AppData\\Local\\npm-cache\\_logs\\2023-09-21T22_36_51_971Z-debug-0.log'
47 silly logfile }
48 silly logfile error removing log file C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_36_48_155Z-debug-0.log [Error: EPERM: operation not permitted, lstat 'C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_36_48_155Z-debug-0.log'] {
48 silly logfile   errno: -4048,
48 silly logfile   code: 'EPERM',
48 silly logfile   syscall: 'lstat',
48 silly logfile   path: 'C:\\Users\\3TEE\\AppData\\Local\\npm-cache\\_logs\\2023-09-21T22_36_48_155Z-debug-0.log'
48 silly logfile }
49 silly logfile error removing log file C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_36_44_800Z-debug-0.log [Error: EPERM: operation not permitted, lstat 'C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_36_44_800Z-debug-0.log'] {
49 silly logfile   errno: -4048,
49 silly logfile   code: 'EPERM',
49 silly logfile   syscall: 'lstat',
49 silly logfile   path: 'C:\\Users\\3TEE\\AppData\\Local\\npm-cache\\_logs\\2023-09-21T22_36_44_800Z-debug-0.log'
49 silly logfile }
50 silly logfile error removing log file C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_36_40_907Z-debug-0.log [Error: EPERM: operation not permitted, lstat 'C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_36_40_907Z-debug-0.log'] {
50 silly logfile   errno: -4048,
50 silly logfile   code: 'EPERM',
50 silly logfile   syscall: 'lstat',
50 silly logfile   path: 'C:\\Users\\3TEE\\AppData\\Local\\npm-cache\\_logs\\2023-09-21T22_36_40_907Z-debug-0.log'
50 silly logfile }
51 silly logfile error removing log file C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_36_36_712Z-debug-0.log [Error: EPERM: operation not permitted, lstat 'C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_36_36_712Z-debug-0.log'] {
51 silly logfile   errno: -4048,
51 silly logfile   code: 'EPERM',
51 silly logfile   syscall: 'lstat',
51 silly logfile   path: 'C:\\Users\\3TEE\\AppData\\Local\\npm-cache\\_logs\\2023-09-21T22_36_36_712Z-debug-0.log'
51 silly logfile }
52 silly logfile error removing log file C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_36_33_079Z-debug-0.log [Error: EPERM: operation not permitted, lstat 'C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_36_33_079Z-debug-0.log'] {
52 silly logfile   errno: -4048,
52 silly logfile   code: 'EPERM',
52 silly logfile   syscall: 'lstat',
52 silly logfile   path: 'C:\\Users\\3TEE\\AppData\\Local\\npm-cache\\_logs\\2023-09-21T22_36_33_079Z-debug-0.log'
52 silly logfile }
53 silly logfile error removing log file C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_36_29_737Z-debug-0.log [Error: EPERM: operation not permitted, lstat 'C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_36_29_737Z-debug-0.log'] {
53 silly logfile   errno: -4048,
53 silly logfile   code: 'EPERM',
53 silly logfile   syscall: 'lstat',
53 silly logfile   path: 'C:\\Users\\3TEE\\AppData\\Local\\npm-cache\\_logs\\2023-09-21T22_36_29_737Z-debug-0.log'
53 silly logfile }
54 silly logfile error removing log file C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_36_26_662Z-debug-0.log [Error: EPERM: operation not permitted, lstat 'C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_36_26_662Z-debug-0.log'] {
54 silly logfile   errno: -4048,
54 silly logfile   code: 'EPERM',
54 silly logfile   syscall: 'lstat',
54 silly logfile   path: 'C:\\Users\\3TEE\\AppData\\Local\\npm-cache\\_logs\\2023-09-21T22_36_26_662Z-debug-0.log'
54 silly logfile }
55 silly logfile error removing log file C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_36_23_686Z-debug-0.log [Error: EPERM: operation not permitted, lstat 'C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_36_23_686Z-debug-0.log'] {
55 silly logfile   errno: -4048,
55 silly logfile   code: 'EPERM',
55 silly logfile   syscall: 'lstat',
55 silly logfile   path: 'C:\\Users\\3TEE\\AppData\\Local\\npm-cache\\_logs\\2023-09-21T22_36_23_686Z-debug-0.log'
55 silly logfile }
56 silly logfile error removing log file C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_36_20_868Z-debug-0.log [Error: EPERM: operation not permitted, lstat 'C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_36_20_868Z-debug-0.log'] {
56 silly logfile   errno: -4048,
56 silly logfile   code: 'EPERM',
56 silly logfile   syscall: 'lstat',
56 silly logfile   path: 'C:\\Users\\3TEE\\AppData\\Local\\npm-cache\\_logs\\2023-09-21T22_36_20_868Z-debug-0.log'
56 silly logfile }
57 silly logfile error removing log file C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_36_17_146Z-debug-0.log [Error: EPERM: operation not permitted, lstat 'C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_36_17_146Z-debug-0.log'] {
57 silly logfile   errno: -4048,
57 silly logfile   code: 'EPERM',
57 silly logfile   syscall: 'lstat',
57 silly logfile   path: 'C:\\Users\\3TEE\\AppData\\Local\\npm-cache\\_logs\\2023-09-21T22_36_17_146Z-debug-0.log'
57 silly logfile }
58 silly logfile error removing log file C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_34_44_281Z-debug-0.log [Error: EPERM: operation not permitted, lstat 'C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_34_44_281Z-debug-0.log'] {
58 silly logfile   errno: -4048,
58 silly logfile   code: 'EPERM',
58 silly logfile   syscall: 'lstat',
58 silly logfile   path: 'C:\\Users\\3TEE\\AppData\\Local\\npm-cache\\_logs\\2023-09-21T22_34_44_281Z-debug-0.log'
58 silly logfile }
59 silly logfile done cleaning log files
60 timing reify:loadTrees Completed in 856ms
61 timing reify:diffTrees Completed in 19ms
62 silly reify mark retired [
62 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\fsevents'
62 silly reify ]
63 silly reify mark retired [
63 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\swc-darwin-arm64'
63 silly reify ]
64 silly reify mark retired [
64 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\swc-linux-arm64-gnu'
64 silly reify ]
65 silly reify mark retired [
65 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\swc-darwin-x64'
65 silly reify ]
66 silly reify mark retired [
66 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\swc-linux-arm64-musl'
66 silly reify ]
67 silly reify mark retired [
67 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\swc-linux-x64-gnu'
67 silly reify ]
68 silly reify mark retired [
68 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\swc-linux-x64-musl'
68 silly reify ]
69 silly reify mark retired [
69 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\swc-win32-ia32-msvc'
69 silly reify ]
70 silly reify mark retired [
70 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\swc-win32-arm64-msvc'
70 silly reify ]
71 silly reify moves {
71 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\fsevents': 'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\.fsevents-PhVuABwy',
71 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\swc-darwin-arm64': 'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\.swc-darwin-arm64-kiUtjNlN',
71 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\swc-linux-arm64-gnu': 'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\.swc-linux-arm64-gnu-CbdVp5ES',
71 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\swc-darwin-x64': 'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\.swc-darwin-x64-lJnTMTlD',
71 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\swc-linux-arm64-musl': 'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\.swc-linux-arm64-musl-TbQWgQkV',
71 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\swc-linux-x64-gnu': 'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\.swc-linux-x64-gnu-DDPHSuGF',
71 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\swc-linux-x64-musl': 'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\.swc-linux-x64-musl-2ReRsFb7',
71 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\swc-win32-ia32-msvc': 'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\.swc-win32-ia32-msvc-oDfKzvk6',
71 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\swc-win32-arm64-msvc': 'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\.swc-win32-arm64-msvc-QxQWjxiH'
71 silly reify }
72 timing reify:retireShallow Completed in 9ms
73 timing reify:createSparse Completed in 2ms
74 timing reify:loadBundles Completed in 0ms
75 silly audit bulk request {
75 silly audit   '@alloc/quick-lru': [ '5.2.0' ],
75 silly audit   '@babel/code-frame': [ '7.22.5' ],
75 silly audit   '@babel/helper-validator-identifier': [ '7.22.5' ],
75 silly audit   '@babel/highlight': [ '7.22.5' ],
75 silly audit   'ansi-styles': [ '3.2.1', '4.3.0' ],
75 silly audit   chalk: [ '2.4.2', '4.1.2' ],
75 silly audit   'color-convert': [ '1.9.3', '2.0.1' ],
75 silly audit   'color-name': [ '1.1.3', '1.1.4' ],
75 silly audit   'escape-string-regexp': [ '1.0.5', '4.0.0' ],
75 silly audit   'has-flag': [ '3.0.0', '4.0.0' ],
75 silly audit   'supports-color': [ '5.5.0', '7.2.0' ],
75 silly audit   '@babel/runtime': [ '7.22.5' ],
75 silly audit   '@cloudinary-util/url-loader': [ '3.8.2' ],
75 silly audit   '@cloudinary-util/util': [ '2.1.0' ],
75 silly audit   '@cloudinary/transformation-builder-sdk': [ '1.2.9' ],
75 silly audit   '@cloudinary/url-gen': [ '1.10.1' ],
75 silly audit   '@eslint-community/eslint-utils': [ '4.4.0' ],
75 silly audit   '@eslint-community/regexpp': [ '4.5.1' ],
75 silly audit   '@eslint/eslintrc': [ '2.0.3' ],
75 silly audit   '@eslint/js': [ '8.43.0' ],
75 silly audit   '@humanwhocodes/config-array': [ '0.11.10' ],
75 silly audit   '@humanwhocodes/module-importer': [ '1.0.1' ],
75 silly audit   '@humanwhocodes/object-schema': [ '1.2.1' ],
75 silly audit   '@jridgewell/gen-mapping': [ '0.3.3' ],
75 silly audit   '@jridgewell/resolve-uri': [ '3.1.0' ],
75 silly audit   '@jridgewell/set-array': [ '1.1.2' ],
75 silly audit   '@jridgewell/sourcemap-codec': [ '1.4.15', '1.4.14' ],
75 silly audit   '@jridgewell/trace-mapping': [ '0.3.18' ],
75 silly audit   '@mapbox/fusspot': [ '0.4.0' ],
75 silly audit   '@mapbox/geojson-rewind': [ '0.5.2' ],
75 silly audit   'get-stream': [ '6.0.1', '5.2.0' ],
75 silly audit   '@mapbox/jsonlint-lines-primitives': [ '2.0.2' ],
75 silly audit   '@mapbox/mapbox-gl-geocoder': [ '5.0.1' ],
75 silly audit   '@mapbox/mapbox-gl-supported': [ '2.0.1' ],
75 silly audit   '@mapbox/mapbox-sdk': [ '0.13.7' ],
75 silly audit   '@mapbox/parse-mapbox-token': [ '0.2.0' ],
75 silly audit   '@mapbox/point-geometry': [ '0.1.0' ],
75 silly audit   '@mapbox/polyline': [ '1.2.0' ],
75 silly audit   '@mapbox/tiny-sdf': [ '2.0.6' ],
75 silly audit   '@mapbox/unitbezier': [ '0.0.1' ],
75 silly audit   '@mapbox/vector-tile': [ '1.3.1' ],
75 silly audit   '@mapbox/whoots-js': [ '3.1.0' ],
75 silly audit   '@maplibre/maplibre-gl-style-spec': [ '19.2.1' ],
75 silly audit   '@next/env': [ '13.4.6' ],
75 silly audit   '@next/eslint-plugin-next': [ '13.4.6' ],
75 silly audit   '@next/swc-darwin-arm64': [ '13.4.6' ],
75 silly audit   '@next/swc-darwin-x64': [ '13.4.6' ],
75 silly audit   '@next/swc-linux-arm64-gnu': [ '13.4.6' ],
75 silly audit   '@next/swc-linux-arm64-musl': [ '13.4.6' ],
75 silly audit   '@next/swc-linux-x64-gnu': [ '13.4.6' ],
75 silly audit   '@next/swc-linux-x64-musl': [ '13.4.6' ],
75 silly audit   '@next/swc-win32-arm64-msvc': [ '13.4.6' ],
75 silly audit   '@next/swc-win32-ia32-msvc': [ '13.4.6' ],
75 silly audit   '@next/swc-win32-x64-msvc': [ '13.4.6' ],
75 silly audit   '@nodelib/fs.scandir': [ '2.1.5' ],
75 silly audit   '@nodelib/fs.stat': [ '2.0.5' ],
75 silly audit   '@nodelib/fs.walk': [ '1.2.8' ],
75 silly audit   '@pkgr/utils': [ '2.4.1' ],
75 silly audit   '@popperjs/core': [ '2.11.8' ],
75 silly audit   '@rushstack/eslint-patch': [ '1.3.2' ],
75 silly audit   '@sindresorhus/is': [ '4.6.0' ],
75 silly audit   '@swc/helpers': [ '0.5.1' ],
75 silly audit   '@szmarczak/http-timer': [ '4.0.6' ],
75 silly audit   '@types/cacheable-request': [ '6.0.3' ],
75 silly audit   '@types/geojson': [ '7946.0.10' ],
75 silly audit   '@types/http-cache-semantics': [ '4.0.1' ],
75 silly audit   '@types/json5': [ '0.0.29' ],
75 silly audit   '@types/keyv': [ '3.1.4' ],
75 silly audit   '@types/mapbox__mapbox-gl-geocoder': [ '4.7.3' ],
75 silly audit   '@types/mapbox__point-geometry': [ '0.1.2' ],
75 silly audit   '@types/mapbox-gl': [ '2.7.11' ],
75 silly audit   '@types/minimist': [ '1.2.2' ],
75 silly audit   '@types/node': [ '20.3.1' ],
75 silly audit   '@types/normalize-package-data': [ '2.4.1' ],
75 silly audit   '@types/prop-types': [ '15.7.5' ],
75 silly audit   '@types/react': [ '18.2.12' ],
75 silly audit   '@types/react-date-range': [ '1.4.4' ],
75 silly audit   '@types/react-dom': [ '18.2.5' ],
75 silly audit   '@types/responselike': [ '1.0.0' ],
75 silly audit   '@types/scheduler': [ '0.16.3' ],
75 silly audit   '@typescript-eslint/parser': [ '5.59.11' ],
75 silly audit   '@typescript-eslint/scope-manager': [ '5.59.11' ],
75 silly audit   '@typescript-eslint/types': [ '5.59.11' ],
75 silly audit   '@typescript-eslint/typescript-estree': [ '5.59.11' ],
75 silly audit   '@typescript-eslint/visitor-keys': [ '5.59.11' ],
75 silly audit   acorn: [ '8.9.0' ],
75 silly audit   'acorn-jsx': [ '5.3.2' ],
75 silly audit   'ag-grid-community': [ '30.0.6' ],
75 silly audit   'ag-grid-react': [ '30.0.6' ],
75 silly audit   ajv: [ '6.12.6' ],
75 silly audit   'ansi-regex': [ '5.0.1' ],
75 silly audit   'any-promise': [ '1.3.0' ],
75 silly audit   anymatch: [ '3.1.3' ],
75 silly audit   arg: [ '5.0.2' ],
75 silly audit   argparse: [ '2.0.1' ],
75 silly audit   'aria-query': [ '5.2.1' ],
75 silly audit   'arr-union': [ '3.1.0' ],
75 silly audit   'array-buffer-byte-length': [ '1.0.0' ],
75 silly audit   'array-includes': [ '3.1.6' ],
75 silly audit   'array-union': [ '2.1.0' ],
75 silly audit   'array.prototype.flat': [ '1.3.1' ],
75 silly audit   'array.prototype.flatmap': [ '1.3.1' ],
75 silly audit   'array.prototype.tosorted': [ '1.1.1' ],
75 silly audit   arrify: [ '1.0.1' ],
75 silly audit   'assign-symbols': [ '1.0.0' ],
75 silly audit   'ast-types-flow': [ '0.0.7' ],
75 silly audit   asynckit: [ '0.4.0' ],
75 silly audit   autoprefixer: [ '10.4.14' ],
75 silly audit   'available-typed-arrays': [ '1.0.5' ],
75 silly audit   'axe-core': [ '4.7.2' ],
75 silly audit   axios: [ '1.4.0' ],
75 silly audit   'form-data': [ '4.0.0', '3.0.1' ],
75 silly audit   'axobject-query': [ '3.2.1' ],
75 silly audit   'balanced-match': [ '1.0.2' ],
75 silly audit   'base-64': [ '0.1.0' ],
75 silly audit   'big-integer': [ '1.6.51' ],
75 silly audit   'binary-extensions': [ '2.2.0' ],
75 silly audit   'bplist-parser': [ '0.2.0' ],
75 silly audit   'brace-expansion': [ '1.1.11' ],
75 silly audit   braces: [ '3.0.2' ],
75 silly audit   browserslist: [ '4.21.9' ],
75 silly audit   'bundle-name': [ '3.0.0' ],
75 silly audit   busboy: [ '1.6.0' ],
75 silly audit   bytewise: [ '1.1.0' ],
75 silly audit   'bytewise-core': [ '1.2.3' ],
75 silly audit   'cacheable-lookup': [ '5.0.4' ],
75 silly audit   'cacheable-request': [ '7.0.4' ],
75 silly audit   'call-bind': [ '1.0.2' ],
75 silly audit   callsites: [ '3.1.0' ],
75 silly audit   camelcase: [ '5.3.1' ],
75 silly audit   'camelcase-css': [ '2.0.1' ],
75 silly audit   'camelcase-keys': [ '6.2.2' ],
75 silly audit   'quick-lru': [ '4.0.1', '5.1.1' ],
75 silly audit   'caniuse-lite': [ '1.0.30001504' ],
75 silly audit   chokidar: [ '3.5.3' ],
75 silly audit   'glob-parent': [ '5.1.2', '6.0.2' ],
75 silly audit   classnames: [ '2.3.2' ],
75 silly audit   'client-only': [ '0.0.1' ],
75 silly audit   'clone-response': [ '1.0.3' ],
75 silly audit   'combined-stream': [ '1.0.8' ],
75 silly audit   commander: [ '4.1.1' ],
75 silly audit   'concat-map': [ '0.0.1' ],
75 silly audit   'cross-spawn': [ '7.0.3' ],
75 silly audit   csscolorparser: [ '1.0.3' ],
75 silly audit   cssesc: [ '3.0.0' ],
75 silly audit   csstype: [ '3.1.2' ],
75 silly audit   'damerau-levenshtein': [ '1.0.8' ],
75 silly audit   'date-fns': [ '2.30.0' ],
75 silly audit   debug: [ '4.3.4', '3.2.7' ],
75 silly audit   decamelize: [ '1.2.0' ],
75 silly audit   'decamelize-keys': [ '1.1.1' ],
75 silly audit   'map-obj': [ '1.0.1', '4.3.0' ],
75 silly audit   'decompress-response': [ '6.0.0' ],
75 silly audit   'mimic-response': [ '3.1.0', '1.0.1' ],
75 silly audit   'deep-is': [ '0.1.4' ],
75 silly audit   'default-browser': [ '4.0.0' ],
75 silly audit   'default-browser-id': [ '3.0.0' ],
75 silly audit   'defer-to-connect': [ '2.0.1' ],
75 silly audit   'define-lazy-prop': [ '3.0.0' ],
75 silly audit   'define-properties': [ '1.2.0' ],
75 silly audit   'delayed-stream': [ '1.0.0' ],
75 silly audit   dequal: [ '2.0.3' ],
75 silly audit   didyoumean: [ '1.2.2' ],
75 silly audit   'dir-glob': [ '3.0.1' ],
75 silly audit   dlv: [ '1.1.3' ],
75 silly audit   doctrine: [ '3.0.0', '2.1.0' ],
75 silly audit   earcut: [ '2.2.4' ],
75 silly audit   'electron-to-chromium': [ '1.4.433' ],
75 silly audit   'emoji-regex': [ '9.2.2' ],
75 silly audit   'end-of-stream': [ '1.4.4' ],
75 silly audit   'enhanced-resolve': [ '5.15.0' ],
75 silly audit   'error-ex': [ '1.3.2' ],
75 silly audit   'es-abstract': [ '1.21.2' ],
75 silly audit   'es-set-tostringtag': [ '2.0.1' ],
75 silly audit   'es-shim-unscopables': [ '1.0.0' ],
75 silly audit   'es-to-primitive': [ '1.2.1' ],
75 silly audit   escalade: [ '3.1.1' ],
75 silly audit   eslint: [ '8.43.0' ],
75 silly audit   'eslint-config-next': [ '13.4.6' ],
75 silly audit   'eslint-import-resolver-node': [ '0.3.7' ],
75 silly audit   'eslint-import-resolver-typescript': [ '3.5.5' ],
75 silly audit   globby: [ '13.2.0', '11.1.0' ],
75 silly audit   slash: [ '4.0.0', '3.0.0' ],
75 silly audit   'eslint-module-utils': [ '2.8.0' ],
75 silly audit   'eslint-plugin-import': [ '2.27.5' ],
75 silly audit   semver: [ '6.3.0', '5.7.1', '7.5.2' ],
75 silly audit   'eslint-plugin-jsx-a11y': [ '6.7.1' ],
75 silly audit   'eslint-plugin-react': [ '7.32.2' ],
75 silly audit   'eslint-plugin-react-hooks': [ '4.6.0' ],
75 silly audit   resolve: [ '2.0.0-next.4', '1.22.2' ],
75 silly audit   'eslint-scope': [ '7.2.0' ],
75 silly audit   'eslint-visitor-keys': [ '3.4.1' ],
75 silly audit   espree: [ '9.5.2' ],
75 silly audit   esquery: [ '1.5.0' ],
75 silly audit   esrecurse: [ '4.3.0' ],
75 silly audit   estraverse: [ '5.3.0' ],
75 silly audit   esutils: [ '2.0.3' ],
75 silly audit   eventemitter3: [ '3.1.2' ],
75 silly audit   events: [ '3.3.0' ],
75 silly audit   execa: [ '7.1.1', '5.1.1' ],
75 silly audit   'extend-shallow': [ '2.0.1', '3.0.2' ],
75 silly audit   'fast-deep-equal': [ '3.1.3' ],
75 silly audit   'fast-glob': [ '3.2.12' ],
75 silly audit   'fast-json-stable-stringify': [ '2.1.0' ],
75 silly audit   'fast-levenshtein': [ '2.0.6' ],
75 silly audit   fastq: [ '1.15.0' ],
75 silly audit   'file-entry-cache': [ '6.0.1' ],
75 silly audit   'fill-range': [ '7.0.1' ],
75 silly audit   'find-up': [ '5.0.0', '4.1.0' ],
75 silly audit   'flat-cache': [ '3.0.4' ],
75 silly audit   flatted: [ '3.2.7' ],
75 silly audit   'follow-redirects': [ '1.15.2' ],
75 silly audit   'for-each': [ '0.3.3' ],
75 silly audit   'fraction.js': [ '4.2.0' ],
75 silly audit   'fs.realpath': [ '1.0.0' ],
75 silly audit   fsevents: [ '2.3.3' ],
75 silly audit   'function-bind': [ '1.1.1' ],
75 silly audit   'function.prototype.name': [ '1.1.5' ],
75 silly audit   'functions-have-names': [ '1.2.3' ],
75 silly audit   fuzzy: [ '0.1.3' ],
75 silly audit   'geojson-vt': [ '3.2.1' ],
75 silly audit   'get-intrinsic': [ '1.2.1' ],
75 silly audit   'get-symbol-description': [ '1.0.0' ],
75 silly audit   'get-tsconfig': [ '4.6.0' ],
75 silly audit   'get-value': [ '2.0.6' ],
75 silly audit   'gl-matrix': [ '3.4.3' ],
75 silly audit   glob: [ '7.1.7', '7.1.6' ],
75 silly audit   'glob-to-regexp': [ '0.4.1' ],
75 silly audit   globals: [ '13.20.0' ],
75 silly audit   globalthis: [ '1.0.3' ],
75 silly audit   gopd: [ '1.0.1' ],
75 silly audit   got: [ '11.8.6' ],
75 silly audit   'graceful-fs': [ '4.2.11' ],
75 silly audit   graphemer: [ '1.4.0' ],
75 silly audit   'grid-index': [ '1.1.0' ],
75 silly audit   'hard-rejection': [ '2.1.0' ],
75 silly audit   has: [ '1.0.3' ],
75 silly audit   'has-bigints': [ '1.0.2' ],
75 silly audit   'has-property-descriptors': [ '1.0.0' ],
75 silly audit   'has-proto': [ '1.0.1' ],
75 silly audit   'has-symbols': [ '1.0.3' ],
75 silly audit   'has-tostringtag': [ '1.0.0' ],
75 silly audit   'hosted-git-info': [ '2.8.9' ],
75 silly audit   'http-cache-semantics': [ '4.1.1' ],
75 silly audit   'http2-wrapper': [ '1.0.3' ],
75 silly audit   'human-signals': [ '4.3.1', '2.1.0' ],
75 silly audit   ieee754: [ '1.2.1' ],
75 silly audit   ignore: [ '5.2.4' ],
75 silly audit   'import-fresh': [ '3.3.0' ],
75 silly audit   imurmurhash: [ '0.1.4' ],
75 silly audit   'indent-string': [ '4.0.0' ],
75 silly audit   inflight: [ '1.0.6' ],
75 silly audit   inherits: [ '2.0.4' ],
75 silly audit   'internal-slot': [ '1.0.5' ],
75 silly audit   'is-array-buffer': [ '3.0.2' ],
75 silly audit   'is-arrayish': [ '0.2.1' ],
75 silly audit   'is-bigint': [ '1.0.4' ],
75 silly audit   'is-binary-path': [ '2.1.0' ],
75 silly audit   'is-boolean-object': [ '1.1.2' ],
75 silly audit   'is-callable': [ '1.2.7' ],
75 silly audit   'is-core-module': [ '2.12.1' ],
75 silly audit   'is-date-object': [ '1.0.5' ],
75 silly audit   'is-docker': [ '3.0.0', '2.2.1' ],
75 silly audit   'is-extendable': [ '0.1.1', '1.0.1' ],
75 silly audit   'is-extglob': [ '2.1.1' ],
75 silly audit   'is-glob': [ '4.0.3' ],
75 silly audit   'is-inside-container': [ '1.0.0' ],
75 silly audit   'is-negative-zero': [ '2.0.2' ],
75 silly audit   'is-number': [ '7.0.0' ],
75 silly audit   'is-number-object': [ '1.0.7' ],
75 silly audit   'is-path-inside': [ '3.0.3' ],
75 silly audit   'is-plain-obj': [ '1.1.0' ],
75 silly audit   'is-plain-object': [ '2.0.4' ],
75 silly audit   'is-regex': [ '1.1.4' ],
75 silly audit   'is-shared-array-buffer': [ '1.0.2' ],
75 silly audit   'is-stream': [ '3.0.0', '2.0.1' ],
75 silly audit   'is-string': [ '1.0.7' ],
75 silly audit   'is-symbol': [ '1.0.4' ],
75 silly audit   'is-typed-array': [ '1.1.10' ],
75 silly audit   'is-weakref': [ '1.0.2' ],
75 silly audit   'is-wsl': [ '2.2.0' ],
75 silly audit   isexe: [ '2.0.0' ],
75 silly audit   isobject: [ '3.0.1' ],
75 silly audit   jiti: [ '1.18.2' ],
75 silly audit   'js-tokens': [ '4.0.0' ],
75 silly audit   'js-yaml': [ '4.1.0' ],
75 silly audit   'json-buffer': [ '3.0.1' ],
75 silly audit   'json-parse-even-better-errors': [ '2.3.1' ],
75 silly audit   'json-schema-traverse': [ '0.4.1' ],
75 silly audit   'json-stable-stringify-without-jsonify': [ '1.0.1' ],
75 silly audit   'json-stringify-pretty-compact': [ '3.0.0' ],
75 silly audit   json5: [ '1.0.2' ],
75 silly audit   'jsx-ast-utils': [ '3.3.3' ],
75 silly audit   kdbush: [ '4.0.2' ],
75 silly audit   keyv: [ '4.5.2' ],
75 silly audit   'kind-of': [ '6.0.3' ],
75 silly audit   'language-subtag-registry': [ '0.3.22' ],
75 silly audit   'language-tags': [ '1.0.5' ],
75 silly audit   levn: [ '0.4.1' ],
75 silly audit   lilconfig: [ '2.1.0' ],
75 silly audit   'lines-and-columns': [ '1.2.4' ],
75 silly audit   'locate-path': [ '6.0.0', '5.0.0' ],
75 silly audit   'lodash.debounce': [ '4.0.8' ],
75 silly audit   'lodash.merge': [ '4.6.2' ],
75 silly audit   'loose-envify': [ '1.4.0' ],
75 silly audit   'lowercase-keys': [ '2.0.0' ],
75 silly audit   'lru-cache': [ '6.0.0' ],
75 silly audit   'mapbox-gl': [ '2.15.0' ],
75 silly audit   meow: [ '6.1.1' ],
75 silly audit   'type-fest': [ '0.13.1', '0.8.1', '0.6.0', '0.20.2' ],
75 silly audit   'merge-stream': [ '2.0.0' ],
75 silly audit   merge2: [ '1.4.1' ],
75 silly audit   micromatch: [ '4.0.5' ],
75 silly audit   'mime-db': [ '1.52.0' ],
75 silly audit   'mime-types': [ '2.1.35' ],
75 silly audit   'mimic-fn': [ '4.0.0', '2.1.0' ],
75 silly audit   'min-indent': [ '1.0.1' ],
75 silly audit   minimatch: [ '3.1.2' ],
75 silly audit   minimist: [ '1.2.8' ],
75 silly audit   'minimist-options': [ '4.1.0' ],
75 silly audit   ms: [ '2.1.2' ],
75 silly audit   'murmurhash-js': [ '1.0.0' ],
75 silly audit   mz: [ '2.7.0' ],
75 silly audit   nanoid: [ '3.3.6' ],
75 silly audit   'natural-compare': [ '1.4.0' ],
75 silly audit   next: [ '13.4.6' ],
75 silly audit   'next-cloudinary': [ '4.13.1' ],
75 silly audit   postcss: [ '8.4.14', '8.4.24' ],
75 silly audit   'node-releases': [ '2.0.12' ],
75 silly audit   'normalize-package-data': [ '2.5.0' ],
75 silly audit   'normalize-path': [ '3.0.0' ],
75 silly audit   'normalize-range': [ '0.1.2' ],
75 silly audit   'normalize-url': [ '6.1.0' ],
75 silly audit   'npm-run-path': [ '5.1.0', '4.0.1' ],
75 silly audit   'path-key': [ '4.0.0', '3.1.1' ],
75 silly audit   'object-assign': [ '4.1.1' ],
75 silly audit   'object-hash': [ '3.0.0' ],
75 silly audit   'object-inspect': [ '1.12.3' ],
75 silly audit   'object-keys': [ '1.1.1' ],
75 silly audit   'object.assign': [ '4.1.4' ],
75 silly audit   'object.entries': [ '1.1.6' ],
75 silly audit   'object.fromentries': [ '2.0.6' ],
75 silly audit   'object.hasown': [ '1.1.2' ],
75 silly audit   'object.values': [ '1.1.6' ],
75 silly audit   once: [ '1.4.0' ],
75 silly audit   onetime: [ '6.0.0', '5.1.2' ],
75 silly audit   open: [ '9.1.0' ],
75 silly audit   optionator: [ '0.9.1' ],
75 silly audit   'p-cancelable': [ '2.1.1' ],
75 silly audit   'p-limit': [ '3.1.0', '2.3.0' ],
75 silly audit   'p-locate': [ '5.0.0', '4.1.0' ],
75 silly audit   'p-try': [ '2.2.0' ],
75 silly audit   'parent-module': [ '1.0.1' ],
75 silly audit   'parse-json': [ '5.2.0' ],
75 silly audit   'path-exists': [ '4.0.0' ],
75 silly audit   'path-is-absolute': [ '1.0.1' ],
75 silly audit   'path-parse': [ '1.0.7' ],
75 silly audit   'path-type': [ '4.0.0' ],
75 silly audit   pbf: [ '3.2.1' ],
75 silly audit   picocolors: [ '1.0.0' ],
75 silly audit   picomatch: [ '2.3.1' ],
75 silly audit   pify: [ '2.3.0' ],
75 silly audit   pirates: [ '4.0.5' ],
75 silly audit   'postcss-import': [ '15.1.0' ],
75 silly audit   'postcss-js': [ '4.0.1' ],
75 silly audit   'postcss-load-config': [ '4.0.1' ],
75 silly audit   'postcss-nested': [ '6.0.1' ],
75 silly audit   'postcss-selector-parser': [ '6.0.13' ],
75 silly audit   'postcss-value-parser': [ '4.2.0' ],
75 silly audit   potpack: [ '2.0.0' ],
75 silly audit   'prelude-ls': [ '1.2.1' ],
75 silly audit   'prop-types': [ '15.8.1' ],
75 silly audit   'protocol-buffers-schema': [ '3.6.0' ],
75 silly audit   'proxy-from-env': [ '1.1.0' ],
75 silly audit   pump: [ '3.0.0' ],
75 silly audit   punycode: [ '2.3.0' ],
75 silly audit   'queue-microtask': [ '1.2.3' ],
75 silly audit   quickselect: [ '2.0.0' ],
75 silly audit   react: [ '18.2.0' ],
75 silly audit   'react-confetti': [ '6.1.0' ],
75 silly audit   'react-date-range': [ '1.4.0' ],
75 silly audit   'react-datepicker': [ '4.15.0' ],
75 silly audit   'react-dom': [ '18.2.0' ],
75 silly audit   'react-fast-compare': [ '3.2.2' ],
75 silly audit   'react-icons': [ '4.10.1' ],
75 silly audit   'react-is': [ '16.13.1' ],
75 silly audit   'react-list': [ '0.8.17' ],
75 silly audit   'react-map-gl': [ '7.1.2' ],
75 silly audit   'react-onclickoutside': [ '6.13.0' ],
75 silly audit   'react-popper': [ '2.3.0' ],
75 silly audit   'read-cache': [ '1.0.0' ],
75 silly audit   'read-pkg': [ '5.2.0' ],
75 silly audit   'read-pkg-up': [ '7.0.1' ],
75 silly audit   readdirp: [ '3.6.0' ],
75 silly audit   redent: [ '3.0.0' ],
75 silly audit   'regenerator-runtime': [ '0.13.11' ],
75 silly audit   'regexp.prototype.flags': [ '1.5.0' ],
75 silly audit   'resolve-alpn': [ '1.2.1' ],
75 silly audit   'resolve-from': [ '4.0.0' ],
75 silly audit   'resolve-pkg-maps': [ '1.0.0' ],
75 silly audit   'resolve-protobuf-schema': [ '2.1.0' ],
75 silly audit   responselike: [ '2.0.1' ],
75 silly audit   reusify: [ '1.0.4' ],
75 silly audit   rimraf: [ '3.0.2' ],
75 silly audit   'run-applescript': [ '5.0.0' ],
75 silly audit   'strip-final-newline': [ '2.0.0', '3.0.0' ],
75 silly audit   'run-parallel': [ '1.2.0' ],
75 silly audit   rw: [ '1.3.3' ],
75 silly audit   'safe-regex-test': [ '1.0.0' ],
75 silly audit   scheduler: [ '0.23.0' ],
75 silly audit   'set-value': [ '2.0.1' ],
75 silly audit   'shallow-equal': [ '1.2.1' ],
75 silly audit   'shebang-command': [ '2.0.0' ],
75 silly audit   'shebang-regex': [ '3.0.0' ],
75 silly audit   'side-channel': [ '1.0.4' ],
75 silly audit   'signal-exit': [ '3.0.7' ],
75 silly audit   'sort-asc': [ '0.2.0' ],
75 silly audit   'sort-desc': [ '0.2.0' ],
75 silly audit   'sort-object': [ '3.0.3' ],
75 silly audit   'source-map-js': [ '1.0.2' ],
75 silly audit   'spdx-correct': [ '3.2.0' ],
75 silly audit   'spdx-exceptions': [ '2.3.0' ],
75 silly audit   'spdx-expression-parse': [ '3.0.1' ],
75 silly audit   'spdx-license-ids': [ '3.0.13' ],
75 silly audit   'split-string': [ '3.1.0' ],
75 silly audit   streamsearch: [ '1.1.0' ],
75 silly audit   'string.prototype.matchall': [ '4.0.8' ],
75 silly audit   'string.prototype.trim': [ '1.2.7' ],
75 silly audit   'string.prototype.trimend': [ '1.0.6' ],
75 silly audit   'string.prototype.trimstart': [ '1.0.6' ],
75 silly audit   'strip-ansi': [ '6.0.1' ],
75 silly audit   'strip-bom': [ '3.0.0' ],
75 silly audit   'strip-indent': [ '3.0.0' ],
75 silly audit   'strip-json-comments': [ '3.1.1' ],
75 silly audit   'styled-jsx': [ '5.1.1' ],
75 silly audit   subtag: [ '0.5.0' ],
75 silly audit   sucrase: [ '3.32.0' ],
75 silly audit   suggestions: [ '1.7.1' ],
75 silly audit   supercluster: [ '8.0.1' ],
75 silly audit   'supports-preserve-symlinks-flag': [ '1.0.0' ],
75 silly audit   synckit: [ '0.8.5' ],
75 silly audit   tailwindcss: [ '3.3.2' ],
75 silly audit   tapable: [ '2.2.1' ],
75 silly audit   'text-table': [ '0.2.0' ],
75 silly audit   thenify: [ '3.3.1' ],
75 silly audit   'thenify-all': [ '1.6.0' ],
75 silly audit   tinyqueue: [ '2.0.3' ],
75 silly audit   titleize: [ '3.0.0' ],
75 silly audit   'to-regex-range': [ '5.0.1' ],
75 silly audit   'trim-newlines': [ '3.0.1' ],
75 silly audit   'ts-interface-checker': [ '0.1.13' ],
75 silly audit   'tsconfig-paths': [ '3.14.2' ],
75 silly audit   tslib: [ '2.5.3', '1.14.1' ],
75 silly audit   tsutils: [ '3.21.0' ],
75 silly audit   'tween-functions': [ '1.2.0' ],
75 silly audit   'type-check': [ '0.4.0' ],
75 silly audit   'typed-array-length': [ '1.0.4' ],
75 silly audit   typescript: [ '5.1.3' ],
75 silly audit   typewise: [ '1.0.3' ],
75 silly audit   'typewise-core': [ '1.2.0' ],
75 silly audit   'unbox-primitive': [ '1.0.2' ],
75 silly audit   'union-value': [ '1.0.1' ],
75 silly audit   untildify: [ '4.0.0' ],
75 silly audit   'update-browserslist-db': [ '1.0.11' ],
75 silly audit   'uri-js': [ '4.4.1' ],
75 silly audit   'use-sync-external-store': [ '1.2.0' ],
75 silly audit   'util-deprecate': [ '1.0.2' ],
75 silly audit   'validate-npm-package-license': [ '3.0.4' ],
75 silly audit   'vt-pbf': [ '3.1.3' ],
75 silly audit   warning: [ '4.0.3' ],
75 silly audit   watchpack: [ '2.4.0' ],
75 silly audit   which: [ '2.0.2' ],
75 silly audit   'which-boxed-primitive': [ '1.0.2' ],
75 silly audit   'which-typed-array': [ '1.1.9' ],
75 silly audit   'word-wrap': [ '1.2.3' ],
75 silly audit   wrappy: [ '1.0.2' ],
75 silly audit   xtend: [ '4.0.2' ],
75 silly audit   yallist: [ '4.0.0' ],
75 silly audit   yaml: [ '2.3.1' ],
75 silly audit   'yargs-parser': [ '18.1.3' ],
75 silly audit   'yocto-queue': [ '0.1.0' ],
75 silly audit   zod: [ '3.21.4' ],
75 silly audit   zustand: [ '4.3.8' ],
75 silly audit   'airbnb-clone': [ '1.0.0' ]
75 silly audit }
76 verbose reify failed optional dependency E:\extras\Work space\Upwork\Airbnb-clone-pablo-02\nextjs-airbnb-clone-starter\public\node_modules\@next\swc-win32-arm64-msvc
77 silly reify mark deleted [
77 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\swc-win32-arm64-msvc'
77 silly reify ]
78 verbose reify failed optional dependency E:\extras\Work space\Upwork\Airbnb-clone-pablo-02\nextjs-airbnb-clone-starter\public\node_modules\@next\swc-win32-ia32-msvc
79 silly reify mark deleted [
79 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\swc-win32-ia32-msvc'
79 silly reify ]
80 verbose reify failed optional dependency E:\extras\Work space\Upwork\Airbnb-clone-pablo-02\nextjs-airbnb-clone-starter\public\node_modules\@next\swc-linux-x64-musl
81 silly reify mark deleted [
81 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\swc-linux-x64-musl'
81 silly reify ]
82 verbose reify failed optional dependency E:\extras\Work space\Upwork\Airbnb-clone-pablo-02\nextjs-airbnb-clone-starter\public\node_modules\@next\swc-linux-x64-gnu
83 silly reify mark deleted [
83 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\swc-linux-x64-gnu'
83 silly reify ]
84 verbose reify failed optional dependency E:\extras\Work space\Upwork\Airbnb-clone-pablo-02\nextjs-airbnb-clone-starter\public\node_modules\@next\swc-linux-arm64-musl
85 silly reify mark deleted [
85 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\swc-linux-arm64-musl'
85 silly reify ]
86 verbose reify failed optional dependency E:\extras\Work space\Upwork\Airbnb-clone-pablo-02\nextjs-airbnb-clone-starter\public\node_modules\@next\swc-darwin-x64
87 silly reify mark deleted [
87 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\swc-darwin-x64'
87 silly reify ]
88 verbose reify failed optional dependency E:\extras\Work space\Upwork\Airbnb-clone-pablo-02\nextjs-airbnb-clone-starter\public\node_modules\@next\swc-linux-arm64-gnu
89 silly reify mark deleted [
89 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\swc-linux-arm64-gnu'
89 silly reify ]
90 verbose reify failed optional dependency E:\extras\Work space\Upwork\Airbnb-clone-pablo-02\nextjs-airbnb-clone-starter\public\node_modules\@next\swc-darwin-arm64
91 silly reify mark deleted [
91 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\@next\\swc-darwin-arm64'
91 silly reify ]
92 verbose reify failed optional dependency E:\extras\Work space\Upwork\Airbnb-clone-pablo-02\nextjs-airbnb-clone-starter\public\node_modules\fsevents
93 silly reify mark deleted [
93 silly reify   'E:\\extras\\Work space\\Upwork\\Airbnb-clone-pablo-02\\nextjs-airbnb-clone-starter\\public\\node_modules\\fsevents'
93 silly reify ]
94 timing reifyNode:node_modules/@next/swc-win32-arm64-msvc Completed in 58ms
95 timing reifyNode:node_modules/@next/swc-win32-ia32-msvc Completed in 58ms
96 timing reifyNode:node_modules/@next/swc-linux-x64-musl Completed in 58ms
97 timing reifyNode:node_modules/@next/swc-linux-x64-gnu Completed in 58ms
98 timing reifyNode:node_modules/@next/swc-linux-arm64-musl Completed in 58ms
99 timing reifyNode:node_modules/@next/swc-darwin-x64 Completed in 58ms
100 timing reifyNode:node_modules/@next/swc-linux-arm64-gnu Completed in 58ms
101 timing reifyNode:node_modules/@next/swc-darwin-arm64 Completed in 58ms
102 timing reifyNode:node_modules/fsevents Completed in 59ms
103 timing reify:unpack Completed in 59ms
104 timing reify:unretire Completed in 0ms
105 timing build:queue Completed in 5ms
106 timing build:deps Completed in 6ms
107 timing build:queue Completed in 0ms
108 info run airbnb-clone@1.0.0 postinstall .. npm i --prefix public && npm i --prefix admin-ui && npm i --prefix server
109 info run airbnb-clone@1.0.0 postinstall { code: 1, signal: null }
110 timing reify:rollback:createSparse Completed in 2ms
111 timing reify:rollback:retireShallow Completed in 5ms
112 timing command:i Completed in 1293ms
113 verbose stack Error: command failed
113 verbose stack     at ChildProcess.<anonymous> (C:\Program Files\nodejs\node_modules\npm\node_modules\@npmcli\promise-spawn\lib\index.js:53:27)
113 verbose stack     at ChildProcess.emit (node:events:514:28)
113 verbose stack     at maybeClose (node:internal/child_process:1091:16)
113 verbose stack     at Socket.<anonymous> (node:internal/child_process:449:11)
113 verbose stack     at Socket.emit (node:events:514:28)
113 verbose stack     at Pipe.<anonymous> (node:net:323:12)
114 verbose pkgid airbnb-clone@1.0.0
115 verbose cwd E:\extras\Work space\Upwork\Airbnb-clone-pablo-02\nextjs-airbnb-clone-starter
116 verbose Windows_NT 10.0.19045
117 verbose node v18.17.1
118 verbose npm  v9.6.7
119 error code 1
120 error path E:\extras\Work space\Upwork\Airbnb-clone-pablo-02\nextjs-airbnb-clone-starter
121 error command failed
122 error command C:\Windows\system32\cmd.exe /d /s /c npm i --prefix public && npm i --prefix admin-ui && npm i --prefix server
123 error 'npm' is not recognized as an internal or external command,
123 error operable program or batch file.
124 verbose exit 1
125 timing npm Completed in 2522ms
126 verbose unfinished npm timer reify 1695335834769
127 verbose unfinished npm timer reify:audit 1695335835662
128 verbose unfinished npm timer auditReport:getReport 1695335835662
129 verbose unfinished npm timer reify:build 1695335835735
130 verbose unfinished npm timer build 1695335835736
131 verbose unfinished npm timer build:links 1695335835742
132 verbose unfinished npm timer build:run:postinstall 1695335835742
133 verbose unfinished npm timer build:run:postinstall:.. 1695335835743
134 verbose code 1
135 error A complete log of this run can be found in: C:\Users\3TEE\AppData\Local\npm-cache\_logs\2023-09-21T22_37_13_539Z-debug-0.log
