<div align="center">
  <h1><code>bench</code></h1>
  <p>
    <strong>📊 Daily benchmarks of deno & node HTTP frameworks</strong>
  </p>
  <br>
  <p align="center">
    <a alt="Bench" href="https://github.com/denosaurs/bench/actions">
      <img src="https://img.shields.io/github/workflow/status/denosaurs/bench/bench" />
    </a>
  </p>
</div>

# Table of Contents

- [Overview](#overview)
  - [Hello, bench!](#hello-bench)
- [Frameworks](#frameworks)
  - [Abc](#abc)
  - [Alosaur](#alosaur)
  - [Aqua](#aqua)
  - [Bun](#bun)
  - [Deno](#deno)
  - [Dinatra](#dinatra)
  - [Drash](#drash)
  - [Express](#express)
  - [Fast](#fast)
  - [Fastify](#fastify)
  - [Hono](#hono)
  - [http](#http)
  - [Little](#little)
  - [Node](#node)
  - [Oak](#oak)
  - [Opine](#opine)
  - [Reno](#reno)
  - [Router](#router)
  - [tinyhttp](#tinyhttp)
  - [Servest](#servest)
- [Benchmarks](#benchmarks)
  - [Hello, bench!](#hello-bench-1)
    - [Abc](#abc-1)
    - [Alosaur](#alosaur-1)
    - [Aqua](#aqua-1)
    - [Bun](#bun-1)
    - [Deno](#deno-1)
    - [Dinatra](#dinatra-1)
    - [Drash](#drash-1)
    - [Express](#express-1)
    - [Fast](#fast-1)
    - [Fastify](#fastify-1)
    - [Hono](#hono-1)
    - [http](#http-1)
    - [Little](#little-1)
    - [Node](#node-1)
    - [Oak](#oak-1)
    - [Opine](#opine-1)
    - [Reno](#reno-1)
    - [Router](#router-1)
    - [tinyhttp](#tinyhttp-1)
    - [Servest](#servest-1)

# Overview

## Hello, bench!

| Framework | Average  | Stddev  | Min      | Max      | Total     |
| --------- | -------- | ------- | -------- | -------- | --------- |
| Deno      | 42416.00 | 3214.21 | 32989.00 | 44371.00 | 424156.00 |
| Node      | 41336.81 | 4735.32 | 27205.00 | 43535.00 | 413314.00 |
| http      | 41072.73 | 3218.77 | 30960.00 | 42634.00 | 451799.00 |
| Hono      | 39546.40 | 3342.91 | 29746.00 | 41836.00 | 395408.00 |
| Bun       | 39039.20 | 2200.40 | 32494.00 | 40133.00 | 390410.00 |
| Fast      | 38512.73 | 3195.32 | 28542.00 | 40069.00 | 423632.00 |
| Fastify   | 36899.64 | 4771.42 | 21866.00 | 38891.00 | 405841.00 |
| Reno      | 31320.00 | 2191.13 | 24811.00 | 32378.00 | 313198.00 |
| Alosaur   | 30520.00 | 6302.97 | 17489.00 | 35680.00 | 305171.00 |
| Router    | 28602.91 | 1720.53 | 23227.00 | 29582.00 | 314644.00 |
| Oak       | 25254.55 | 2055.47 | 18967.00 | 26550.00 | 277783.00 |
| Aqua      | 23302.55 | 1716.53 | 17891.00 | 24069.00 | 256303.00 |
| Drash     | 16694.19 | 1315.50 | 12549.00 | 17279.00 | 183630.00 |
| Abc       | 15340.00 | 3131.98 | 8529.00  | 17374.00 | 168728.00 |
| Little    | 13750.19 | 1081.77 | 10356.00 | 14246.00 | 151253.00 |
| Dinatra   | 11390.19 | 944.84  | 8486.00  | 11914.00 | 125290.00 |
| Opine     | 9768.60  | 867.65  | 7187.00  | 10214.00 | 97692.00  |
| Express   | 6954.64  | 1068.58 | 3676.00  | 7522.00  | 76496.00  |
| Servest   | 5411.60  | 433.55  | 4119.00  | 5677.00  | 54109.00  |
| tinyhttp  | 3894.70  | 573.41  | 2976.00  | 4747.00  | 38943.00  |

# Frameworks

## [Abc](https://deno.land/x/abc)

A better Deno framework to create web application

## [Alosaur](https://deno.land/x/alosaur)

Deno web framework with many decorators

## [Aqua](https://deno.land/x/aqua)

A minimal and fast 🏃 web framework for Deno

## [Bun](https://bun.sh/)

Bun is a fast all-in-one JavaScript runtime

## [Deno](https://deno.land/)

A modern runtime for JavaScript and TypeScript

## [Dinatra](https://github.com/syumai/dinatra)

Sinatra like light weight web app framework for deno.

## [Drash](https://deno.land/x/drash)

A REST microframework for Deno's HTTP server with zero dependencies.

## [Express](https://expressjs.com/)

Fast, unopinionated, minimalist web framework for Node.js

## [Fast](https://deno.land/x/fast)

Small web framework with near-native performance.

## [Fastify](https://www.fastify.io/)

Fast and low overhead web framework, for Node.js

## [Hono](https://github.com/honojs/hono)

Ultrafast web framework for Cloudflare Workers and Deno. Fast, but not only
fast.

## [http](https://deno.land/std/http)

The deno standard library http server

## [Little](https://deno.land/x/little)

A minimalistic connect-like web framework. Automatically works out of the box
with Deno Deploy, Deno's Native HTTP and Deno's Standard HTTP server.

## [Node](https://nodejs.org/)

Node.js® is a JavaScript runtime built on Chrome's V8 JavaScript engine.

## [Oak](https://deno.land/x/oak)

A middleware framework for Deno's native HTTP server, Deno Deploy and Node.js
16.5 and later. It also includes a middleware router.

## [Opine](https://deno.land/x/opine)

Fast, minimalist web framework for Deno ported from ExpressJS.

## [Reno](https://deno.land/x/reno)

A thin, testable routing library designed to sit on top of Deno's standard HTTP
module.

## [Router](https://crux.land/router@0.0.12)

The tiny, modern and fast router by the denosaurs for deno and deno deploy. Used
by projects like fresh

## [tinyhttp](https://deno.land/x/tinyhttp)

🦕 Deno port of tinyhttp, 0-legacy, tiny & fast web framework

## [Servest](https://servestjs.org/)

🌾A progressive http server for Deno🌾

# Benchmarks

## Hello, bench!

A simple benchmark which expects a response simply containing the text
"`Hello, Bench!`"

### [Abc](#abc)

| **Stat**      | Average  | Stddev  | Min     | Max      | Total     |
| ------------- | -------- | ------- | ------- | -------- | --------- |
| **Req/Sec**   | 15340.00 | 3131.98 | 8529.00 | 17374.00 | 168728.00 |
| **Bytes/Sec** | 1.43 MB  | 291 kB  | 793 kB  | 1.62 MB  | 15.7 MB   |
| **Latency**   | 2ms      | 970µs   | 1ms     | 22ms     | N/A       |

| **Stat**      | 1       | 2.5     | 50       | 90       | 97.5     | 99       |
| ------------- | ------- | ------- | -------- | -------- | -------- | -------- |
| **Req/Sec**   | 8535.00 | 8535.00 | 17071.00 | 17343.00 | 17375.00 | 17375.00 |
| **Bytes/Sec** | 794 kB  | 794 kB  | 1.59 MB  | 1.61 MB  | 1.62 MB  | 1.62 MB  |
| **Latency**   | 1ms     | 2ms     | 2ms      | 4ms      | 4ms      | 5ms      |

### [Alosaur](#alosaur)

| **Stat**      | Average  | Stddev  | Min      | Max      | Total     |
| ------------- | -------- | ------- | -------- | -------- | --------- |
| **Req/Sec**   | 30520.00 | 6302.97 | 17489.00 | 35680.00 | 305171.00 |
| **Bytes/Sec** | 3.42 MB  | 706 kB  | 1.96 MB  | 4 MB     | 34.2 MB   |
| **Latency**   | 1ms      | 820µs   | 1ms      | 32ms     | N/A       |

| **Stat**      | 1        | 2.5      | 50       | 90       | 97.5     | 99       |
| ------------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec**   | 17503.00 | 17503.00 | 34239.00 | 35423.00 | 35711.00 | 35711.00 |
| **Bytes/Sec** | 1.96 MB  | 1.96 MB  | 3.83 MB  | 3.97 MB  | 4 MB     | 4 MB     |
| **Latency**   | 0ms      | 0ms      | 1ms      | 2ms      | 2ms      | 4ms      |

### [Aqua](#aqua)

| **Stat**      | Average  | Stddev  | Min      | Max      | Total     |
| ------------- | -------- | ------- | -------- | -------- | --------- |
| **Req/Sec**   | 23302.55 | 1716.53 | 17891.00 | 24069.00 | 256303.00 |
| **Bytes/Sec** | 3.54 MB  | 261 kB  | 2.72 MB  | 3.66 MB  | 39 MB     |
| **Latency**   | 1ms      | 700µs   | 1ms      | 39ms     | N/A       |

| **Stat**      | 1        | 2.5      | 50       | 90       | 97.5     | 99       |
| ------------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec**   | 17903.00 | 17903.00 | 23855.00 | 24015.00 | 24079.00 | 24079.00 |
| **Bytes/Sec** | 2.72 MB  | 2.72 MB  | 3.62 MB  | 3.65 MB  | 3.66 MB  | 3.66 MB  |
| **Latency**   | 1ms      | 1ms      | 1ms      | 1ms      | 2ms      | 3ms      |

### [Bun](#bun)

| **Stat**      | Average  | Stddev  | Min      | Max      | Total     |
| ------------- | -------- | ------- | -------- | -------- | --------- |
| **Req/Sec**   | 39039.20 | 2200.40 | 32494.00 | 40133.00 | 390410.00 |
| **Bytes/Sec** | 3.59 MB  | 202 kB  | 2.99 MB  | 3.69 MB  | 35.9 MB   |
| **Latency**   | 170µs    | 470µs   | 1ms      | 17ms     | N/A       |

| **Stat**      | 1        | 2.5      | 50       | 90       | 97.5     | 99       |
| ------------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec**   | 32495.00 | 32495.00 | 39871.00 | 40031.00 | 40159.00 | 40159.00 |
| **Bytes/Sec** | 2.99 MB  | 2.99 MB  | 3.67 MB  | 3.68 MB  | 3.69 MB  | 3.69 MB  |
| **Latency**   | 0ms      | 0ms      | 0ms      | 1ms      | 1ms      | 1ms      |

### [Deno](#deno)

| **Stat**      | Average  | Stddev  | Min      | Max      | Total     |
| ------------- | -------- | ------- | -------- | -------- | --------- |
| **Req/Sec**   | 42416.00 | 3214.21 | 32989.00 | 44371.00 | 424156.00 |
| **Bytes/Sec** | 6.45 MB  | 487 kB  | 5.01 MB  | 6.74 MB  | 64.5 MB   |
| **Latency**   | 430µs    | 670µs   | 1ms      | 25ms     | N/A       |

| **Stat**      | 1        | 2.5      | 50       | 90       | 97.5     | 99       |
| ------------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec**   | 32991.00 | 32991.00 | 43327.00 | 44127.00 | 44383.00 | 44383.00 |
| **Bytes/Sec** | 5.02 MB  | 5.02 MB  | 6.59 MB  | 6.71 MB  | 6.75 MB  | 6.75 MB  |
| **Latency**   | 0ms      | 0ms      | 0ms      | 1ms      | 1ms      | 3ms      |

### [Dinatra](#dinatra)

| **Stat**      | Average  | Stddev  | Min     | Max      | Total     |
| ------------- | -------- | ------- | ------- | -------- | --------- |
| **Req/Sec**   | 11390.19 | 944.84  | 8486.00 | 11914.00 | 125290.00 |
| **Bytes/Sec** | 592 kB   | 49.1 kB | 441 kB  | 620 kB   | 6.52 MB   |
| **Latency**   | 3ms      | 1ms     | 1ms     | 56ms     | N/A       |

| **Stat**      | 1       | 2.5     | 50       | 90       | 97.5     | 99       |
| ------------- | ------- | ------- | -------- | -------- | -------- | -------- |
| **Req/Sec**   | 8487.00 | 8487.00 | 11767.00 | 11903.00 | 11919.00 | 11919.00 |
| **Bytes/Sec** | 441 kB  | 441 kB  | 612 kB   | 619 kB   | 620 kB   | 620 kB   |
| **Latency**   | 2ms     | 2ms     | 3ms      | 3ms      | 6ms      | 8ms      |

### [Drash](#drash)

| **Stat**      | Average  | Stddev  | Min      | Max      | Total     |
| ------------- | -------- | ------- | -------- | -------- | --------- |
| **Req/Sec**   | 16694.19 | 1315.50 | 12549.00 | 17279.00 | 183630.00 |
| **Bytes/Sec** | 1.55 MB  | 122 kB  | 1.17 MB  | 1.61 MB  | 17.1 MB   |
| **Latency**   | 2ms      | 670µs   | 1ms      | 44ms     | N/A       |

| **Stat**      | 1        | 2.5      | 50       | 90       | 97.5     | 99       |
| ------------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec**   | 12551.00 | 12551.00 | 17135.00 | 17215.00 | 17279.00 | 17279.00 |
| **Bytes/Sec** | 1.17 MB  | 1.17 MB  | 1.59 MB  | 1.6 MB   | 1.61 MB  | 1.61 MB  |
| **Latency**   | 1ms      | 2ms      | 2ms      | 2ms      | 3ms      | 4ms      |

### [Express](#express)

| **Stat**      | Average | Stddev  | Min     | Max     | Total    |
| ------------- | ------- | ------- | ------- | ------- | -------- |
| **Req/Sec**   | 6954.64 | 1068.58 | 3676.00 | 7522.00 | 76496.00 |
| **Bytes/Sec** | 1.67 MB | 256 kB  | 882 kB  | 1.81 MB | 18.4 MB  |
| **Latency**   | 5ms     | 1ms     | 1ms     | 48ms    | N/A      |

| **Stat**      | 1       | 2.5     | 50      | 90      | 97.5    | 99      |
| ------------- | ------- | ------- | ------- | ------- | ------- | ------- |
| **Req/Sec**   | 3677.00 | 3677.00 | 7363.00 | 7443.00 | 7523.00 | 7523.00 |
| **Bytes/Sec** | 883 kB  | 883 kB  | 1.77 MB | 1.79 MB | 1.81 MB | 1.81 MB |
| **Latency**   | 4ms     | 4ms     | 5ms     | 7ms     | 11ms    | 13ms    |

### [Fast](#fast)

| **Stat**      | Average  | Stddev  | Min      | Max      | Total     |
| ------------- | -------- | ------- | -------- | -------- | --------- |
| **Req/Sec**   | 38512.73 | 3195.32 | 28542.00 | 40069.00 | 423632.00 |
| **Bytes/Sec** | 5.85 MB  | 485 kB  | 4.34 MB  | 6.09 MB  | 64.4 MB   |
| **Latency**   | 230µs    | 960µs   | 1ms      | 20ms     | N/A       |

| **Stat**      | 1        | 2.5      | 50       | 90       | 97.5     | 99       |
| ------------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec**   | 28543.00 | 28543.00 | 39679.00 | 39999.00 | 40095.00 | 40095.00 |
| **Bytes/Sec** | 4.34 MB  | 4.34 MB  | 6.03 MB  | 6.08 MB  | 6.09 MB  | 6.09 MB  |
| **Latency**   | 0ms      | 0ms      | 0ms      | 1ms      | 2ms      | 6ms      |

### [Fastify](#fastify)

| **Stat**      | Average  | Stddev  | Min      | Max      | Total     |
| ------------- | -------- | ------- | -------- | -------- | --------- |
| **Req/Sec**   | 36899.64 | 4771.42 | 21866.00 | 38891.00 | 405841.00 |
| **Bytes/Sec** | 6.57 MB  | 849 kB  | 3.89 MB  | 6.92 MB  | 72.2 MB   |
| **Latency**   | 390µs    | 770µs   | 1ms      | 33ms     | N/A       |

| **Stat**      | 1        | 2.5      | 50       | 90       | 97.5     | 99       |
| ------------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec**   | 21871.00 | 21871.00 | 38591.00 | 38719.00 | 38911.00 | 38911.00 |
| **Bytes/Sec** | 3.89 MB  | 3.89 MB  | 6.86 MB  | 6.89 MB  | 6.93 MB  | 6.93 MB  |
| **Latency**   | 0ms      | 0ms      | 0ms      | 1ms      | 1ms      | 2ms      |

### [Hono](#hono)

| **Stat**      | Average  | Stddev  | Min      | Max      | Total     |
| ------------- | -------- | ------- | -------- | -------- | --------- |
| **Req/Sec**   | 39546.40 | 3342.91 | 29746.00 | 41836.00 | 395408.00 |
| **Bytes/Sec** | 6.05 MB  | 511 kB  | 4.55 MB  | 6.4 MB   | 60.5 MB   |
| **Latency**   | 170µs    | 660µs   | 1ms      | 22ms     | N/A       |

| **Stat**      | 1        | 2.5      | 50       | 90       | 97.5     | 99       |
| ------------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec**   | 29759.00 | 29759.00 | 40735.00 | 41119.00 | 41855.00 | 41855.00 |
| **Bytes/Sec** | 4.55 MB  | 4.55 MB  | 6.23 MB  | 6.29 MB  | 6.4 MB   | 6.4 MB   |
| **Latency**   | 0ms      | 0ms      | 0ms      | 1ms      | 2ms      | 3ms      |

### [http](#http)

| **Stat**      | Average  | Stddev  | Min      | Max      | Total     |
| ------------- | -------- | ------- | -------- | -------- | --------- |
| **Req/Sec**   | 41072.73 | 3218.77 | 30960.00 | 42634.00 | 451799.00 |
| **Bytes/Sec** | 6.82 MB  | 535 kB  | 5.14 MB  | 7.08 MB  | 75 MB     |
| **Latency**   | 450µs    | 690µs   | 1ms      | 19ms     | N/A       |

| **Stat**      | 1        | 2.5      | 50       | 90       | 97.5     | 99       |
| ------------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec**   | 30975.00 | 30975.00 | 41951.00 | 42623.00 | 42655.00 | 42655.00 |
| **Bytes/Sec** | 5.14 MB  | 5.14 MB  | 6.97 MB  | 7.08 MB  | 7.08 MB  | 7.08 MB  |
| **Latency**   | 0ms      | 0ms      | 0ms      | 1ms      | 2ms      | 3ms      |

### [Little](#little)

| **Stat**      | Average  | Stddev  | Min      | Max      | Total     |
| ------------- | -------- | ------- | -------- | -------- | --------- |
| **Req/Sec**   | 13750.19 | 1081.77 | 10356.00 | 14246.00 | 151253.00 |
| **Bytes/Sec** | 2.09 MB  | 164 kB  | 1.57 MB  | 2.17 MB  | 23 MB     |
| **Latency**   | 2ms      | 750µs   | 1ms      | 20ms     | N/A       |

| **Stat**      | 1        | 2.5      | 50       | 90       | 97.5     | 99       |
| ------------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec**   | 10359.00 | 10359.00 | 14103.00 | 14207.00 | 14247.00 | 14247.00 |
| **Bytes/Sec** | 1.57 MB  | 1.57 MB  | 2.14 MB  | 2.16 MB  | 2.17 MB  | 2.17 MB  |
| **Latency**   | 1ms      | 2ms      | 2ms      | 3ms      | 4ms      | 6ms      |

### [Node](#node)

| **Stat**      | Average  | Stddev  | Min      | Max      | Total     |
| ------------- | -------- | ------- | -------- | -------- | --------- |
| **Req/Sec**   | 41336.81 | 4735.32 | 27205.00 | 43535.00 | 413314.00 |
| **Bytes/Sec** | 5.62 MB  | 644 kB  | 3.7 MB   | 5.92 MB  | 56.2 MB   |
| **Latency**   | 310µs    | 660µs   | 1ms      | 23ms     | N/A       |

| **Stat**      | 1        | 2.5      | 50       | 90       | 97.5     | 99       |
| ------------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec**   | 27215.00 | 27215.00 | 42751.00 | 43519.00 | 43551.00 | 43551.00 |
| **Bytes/Sec** | 3.7 MB   | 3.7 MB   | 5.81 MB  | 5.91 MB  | 5.92 MB  | 5.92 MB  |
| **Latency**   | 0ms      | 0ms      | 0ms      | 1ms      | 1ms      | 2ms      |

### [Oak](#oak)

| **Stat**      | Average  | Stddev  | Min      | Max      | Total     |
| ------------- | -------- | ------- | -------- | -------- | --------- |
| **Req/Sec**   | 25254.55 | 2055.47 | 18967.00 | 26550.00 | 277783.00 |
| **Bytes/Sec** | 3.86 MB  | 315 kB  | 2.9 MB   | 4.06 MB  | 42.5 MB   |
| **Latency**   | 1ms      | 650µs   | 1ms      | 22ms     | N/A       |

| **Stat**      | 1        | 2.5      | 50       | 90       | 97.5     | 99       |
| ------------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec**   | 18975.00 | 18975.00 | 25919.00 | 26543.00 | 26559.00 | 26559.00 |
| **Bytes/Sec** | 2.9 MB   | 2.9 MB   | 3.96 MB  | 4.06 MB  | 4.06 MB  | 4.06 MB  |
| **Latency**   | 0ms      | 1ms      | 1ms      | 1ms      | 3ms      | 3ms      |

### [Opine](#opine)

| **Stat**      | Average | Stddev | Min     | Max      | Total    |
| ------------- | ------- | ------ | ------- | -------- | -------- |
| **Req/Sec**   | 9768.60 | 867.65 | 7187.00 | 10214.00 | 97692.00 |
| **Bytes/Sec** | 2.09 MB | 186 kB | 1.54 MB | 2.19 MB  | 20.9 MB  |
| **Latency**   | 3ms     | 1ms    | 1ms     | 37ms     | N/A      |

| **Stat**      | 1       | 2.5     | 50      | 90       | 97.5     | 99       |
| ------------- | ------- | ------- | ------- | -------- | -------- | -------- |
| **Req/Sec**   | 7187.00 | 7187.00 | 9983.00 | 10183.00 | 10215.00 | 10215.00 |
| **Bytes/Sec** | 1.54 MB | 1.54 MB | 2.14 MB | 2.18 MB  | 2.19 MB  | 2.19 MB  |
| **Latency**   | 1ms     | 1ms     | 4ms     | 4ms      | 5ms      | 8ms      |

### [Reno](#reno)

| **Stat**      | Average  | Stddev  | Min      | Max      | Total     |
| ------------- | -------- | ------- | -------- | -------- | --------- |
| **Req/Sec**   | 31320.00 | 2191.13 | 24811.00 | 32378.00 | 313198.00 |
| **Bytes/Sec** | 4.76 MB  | 333 kB  | 3.77 MB  | 4.92 MB  | 47.6 MB   |
| **Latency**   | 1ms      | 550µs   | 1ms      | 20ms     | N/A       |

| **Stat**      | 1        | 2.5      | 50       | 90       | 97.5     | 99       |
| ------------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec**   | 24815.00 | 24815.00 | 32015.00 | 32351.00 | 32383.00 | 32383.00 |
| **Bytes/Sec** | 3.77 MB  | 3.77 MB  | 4.87 MB  | 4.92 MB  | 4.92 MB  | 4.92 MB  |
| **Latency**   | 0ms      | 0ms      | 1ms      | 1ms      | 2ms      | 3ms      |

### [Router](#router)

| **Stat**      | Average  | Stddev  | Min      | Max      | Total     |
| ------------- | -------- | ------- | -------- | -------- | --------- |
| **Req/Sec**   | 28602.91 | 1720.53 | 23227.00 | 29582.00 | 314644.00 |
| **Bytes/Sec** | 4.35 MB  | 262 kB  | 3.53 MB  | 4.5 MB   | 47.8 MB   |
| **Latency**   | 1ms      | 530µs   | 1ms      | 22ms     | N/A       |

| **Stat**      | 1        | 2.5      | 50       | 90       | 97.5     | 99       |
| ------------- | -------- | -------- | -------- | -------- | -------- | -------- |
| **Req/Sec**   | 23231.00 | 23231.00 | 29135.00 | 29375.00 | 29583.00 | 29583.00 |
| **Bytes/Sec** | 3.53 MB  | 3.53 MB  | 4.43 MB  | 4.46 MB  | 4.5 MB   | 4.5 MB   |
| **Latency**   | 0ms      | 0ms      | 1ms      | 1ms      | 2ms      | 2ms      |

### [tinyhttp](#tinyhttp)

| **Stat**      | Average | Stddev | Min     | Max     | Total    |
| ------------- | ------- | ------ | ------- | ------- | -------- |
| **Req/Sec**   | 3894.70 | 573.41 | 2976.00 | 4747.00 | 38943.00 |
| **Bytes/Sec** | 448 kB  | 66 kB  | 342 kB  | 546 kB  | 4.48 MB  |
| **Latency**   | 9ms     | 16ms   | 1ms     | 58ms    | N/A      |

| **Stat**      | 1       | 2.5     | 50      | 90      | 97.5    | 99      |
| ------------- | ------- | ------- | ------- | ------- | ------- | ------- |
| **Req/Sec**   | 2977.00 | 2977.00 | 3835.00 | 4719.00 | 4747.00 | 4747.00 |
| **Bytes/Sec** | 342 kB  | 342 kB  | 441 kB  | 543 kB  | 546 kB  | 546 kB  |
| **Latency**   | 0ms     | 0ms     | 2ms     | 44ms    | 47ms    | 48ms    |

### [Servest](#servest)

| **Stat**      | Average | Stddev  | Min     | Max     | Total    |
| ------------- | ------- | ------- | ------- | ------- | -------- |
| **Req/Sec**   | 5411.60 | 433.55  | 4119.00 | 5677.00 | 54109.00 |
| **Bytes/Sec** | 850 kB  | 67.9 kB | 647 kB  | 891 kB  | 8.5 MB   |
| **Latency**   | 6ms     | 2ms     | 1ms     | 49ms    | N/A      |

| **Stat**      | 1       | 2.5     | 50      | 90      | 97.5    | 99      |
| ------------- | ------- | ------- | ------- | ------- | ------- | ------- |
| **Req/Sec**   | 4119.00 | 4119.00 | 5531.00 | 5579.00 | 5679.00 | 5679.00 |
| **Bytes/Sec** | 647 kB  | 647 kB  | 868 kB  | 876 kB  | 891 kB  | 891 kB  |
| **Latency**   | 4ms     | 5ms     | 6ms     | 10ms    | 15ms    | 18ms    |

---

<p align="center">Generated 2022-07-25T00:51:01.348Z</p>
