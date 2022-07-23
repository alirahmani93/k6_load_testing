# k6_load_testing
Grafana k6 is an open-source load testing tool that makes performance testing easy and productive for engineering teams.

Run k6 in docker:
`docker run --rm -i grafana/k6 run --vus 1 --duration 2s - <script.js`


vus: VUs are essentially parallel while(true) loops. Scripts are written in JavaScript,
 as ES6 modules, which allows you to break larger tests into smaller pieces or make reusable pieces as you like.

duration: the test duration.

