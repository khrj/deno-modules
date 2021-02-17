<div align="center">
    <img src="assets/logo.png" width="350" height="350" alt="trains between usb and usb port abstract illustration">
    <h1>Deno modules</h1>
    <p>
        <b>A complete list of all the Deno modules I've made / ported</b>
    </p>
    <p>
        <img alt="runtime - deno" src="https://img.shields.io/badge/runtime-deno-brightgreen" >
        <img alt="total - 8" src="https://img.shields.io/badge/total-8-blue" >
        <img alt="written from scratch - 2" src="https://img.shields.io/badge/written%20from%20scratch-2-blue" >
        <img alt="rewrites - 1" src="https://img.shields.io/badge/rewrites-1-blue" >
        <img alt="ports - 4" src="https://img.shields.io/badge/ports-4-blue">
        <img alt="repacks - 1" src="https://img.shields.io/badge/repacks-1-blue" >
    </p>
    <br>
    <br>
    <br>
</div>


# Table of Contents

- Written from scratch
    - [ngrok](#ngrok)
    - [hcload](#hcload)
- Rewrites
    - [retried](#retried)
- Ports
    - [pQueue](#pQueue)
    - [pRetried](#pRetried)
    - [pTimeout](#pTimeout)
    - [Finity](#Finity)
- Repacks
    - [ee-ts](#ee-ts)

# Written from Scratch

## ngrok

<p>
<img alt="build status" src="https://img.shields.io/github/workflow/status/KhushrajRathod/ngrok/Deno?label=checks" >
<img alt="language" src="https://img.shields.io/github/languages/top/KhushrajRathod/ngrok" >
<img alt="code size" src="https://img.shields.io/github/languages/code-size/KhushrajRathod/ngrok">
<img alt="issues" src="https://img.shields.io/github/issues/KhushrajRathod/ngrok" >
<img alt="license" src="https://img.shields.io/github/license/KhushrajRathod/ngrok">
<img alt="version" src="https://img.shields.io/github/v/release/KhushrajRathod/ngrok">
</p>

<b><a href="https://github.com/KhushrajRathod/ngrok">View on GitHub</a></b> -- <b><a href="https://deno.land/x/ngrok">View on deno.land</a></b>

- Description: Expose your localhost to the web. Ultra-simple deno wrapper for ngrok

## hcload

<p>
<img alt="build status" src="https://img.shields.io/github/workflow/status/KhushrajRathod/hcload/Deno?label=checks" >
<img alt="language" src="https://img.shields.io/github/languages/top/KhushrajRathod/hcload" >
<img alt="code size" src="https://img.shields.io/github/languages/code-size/KhushrajRathod/hcload">
<img alt="issues" src="https://img.shields.io/github/issues/KhushrajRathod/hcload" >
<img alt="license" src="https://img.shields.io/github/license/KhushrajRathod/hcload">
<img alt="version" src="https://img.shields.io/github/v/release/KhushrajRathod/hcload">
</p>

<b><a href="https://github.com/KhushrajRathod/hcload">View on GitHub</a></b> -- <b><a href="https://deno.land/x/hcload">View on deno.land</a></b>

- Description: Easily upload files to the [Hack club](https://hackclub.com) CDN

# Rewrites

## retried

<p>
<img alt="build status" src="https://img.shields.io/github/workflow/status/KhushrajRathod/retried/Deno?label=checks" >
<img alt="language" src="https://img.shields.io/github/languages/top/KhushrajRathod/retried" >
<img alt="code size" src="https://img.shields.io/github/languages/code-size/KhushrajRathod/retried">
<img alt="issues" src="https://img.shields.io/github/issues/KhushrajRathod/retried" >
<img alt="license" src="https://img.shields.io/github/license/KhushrajRathod/retried">
<img alt="version" src="https://img.shields.io/github/v/release/KhushrajRathod/retried">
</p>

- Description: Abstraction for exponential and custom retry strategies for failed operations. 
- Original module: [retry](https://www.npmjs.com/package/retry)
- Changes: Deno, TypeScript, ES6+

# Ports

## pQueue

<p>
<img alt="build status" src="https://img.shields.io/github/workflow/status/KhushrajRathod/pQueue/Deno?label=checks" >
<img alt="language" src="https://img.shields.io/github/languages/top/KhushrajRathod/pQueue" >
<img alt="code size" src="https://img.shields.io/github/languages/code-size/KhushrajRathod/pQueue">
<img alt="issues" src="https://img.shields.io/github/issues/KhushrajRathod/pQueue" >
<img alt="license" src="https://img.shields.io/github/license/KhushrajRathod/pQueue">
<img alt="version" src="https://img.shields.io/github/v/release/KhushrajRathod/pQueue">
</p>

<b><a href="https://github.com/KhushrajRathod/pQueue">View on GitHub</a></b> -- <b><a href="https://deno.land/x/p_queue">View on deno.land</a></b>

- Description: Promise queue with concurrency control. Useful for rate-limiting async (or sync) operations. For example, when interacting with a REST API or when doing CPU/memory intensive tasks.
- Original module: [p-queue](https://www.npmjs.com/package/p-queue)

## pRetried

<p>
<img alt="build status" src="https://img.shields.io/github/workflow/status/KhushrajRathod/pRetried/Deno?label=checks" >
<img alt="language" src="https://img.shields.io/github/languages/top/KhushrajRathod/pRetried" >
<img alt="code size" src="https://img.shields.io/github/languages/code-size/KhushrajRathod/pRetried">
<img alt="issues" src="https://img.shields.io/github/issues/KhushrajRathod/pRetried" >
<img alt="license" src="https://img.shields.io/github/license/KhushrajRathod/pRetried">
<img alt="version" src="https://img.shields.io/github/v/release/KhushrajRathod/pRetried">
</p>

<b><a href="https://github.com/KhushrajRathod/pRetried">View on GitHub</a></b> -- <b><a href="https://deno.land/x/p_retried">View on deno.land</a></b>

- Description: Retry a promise-returning or async function. Abstraction for exponential and custom retry strategies for failed operations
- Original module: [p-retry](https://www.npmjs.com/package/p-retry)

## pTimeout

<p>
<img alt="build status" src="https://img.shields.io/github/workflow/status/KhushrajRathod/pTimeout/Deno?label=checks" >
<img alt="language" src="https://img.shields.io/github/languages/top/KhushrajRathod/pTimeout" >
<img alt="code size" src="https://img.shields.io/github/languages/code-size/KhushrajRathod/pTimeout">
<img alt="issues" src="https://img.shields.io/github/issues/KhushrajRathod/pTimeout" >
<img alt="license" src="https://img.shields.io/github/license/KhushrajRathod/pTimeout">
<img alt="version" src="https://img.shields.io/github/v/release/KhushrajRathod/pTimeout">
</p>

<b><a href="https://github.com/KhushrajRathod/pTimeout">View on GitHub</a></b> -- <b><a href="https://deno.land/x/p_timeout">View on deno.land</a></b>

- Description: Timeout a promise after a specified amount of time
- Original module: [p-timeout](https://www.npmjs.com/package/p-timeout)

## Finity

<p>
<img alt="build status" src="https://img.shields.io/github/workflow/status/KhushrajRathod/finity/Deno?label=checks" >
<img alt="language" src="https://img.shields.io/github/languages/top/KhushrajRathod/Finity" >
<img alt="code size" src="https://img.shields.io/github/languages/code-size/KhushrajRathod/Finity">
<img alt="issues" src="https://img.shields.io/github/issues/KhushrajRathod/Finity" >
<img alt="license" src="https://img.shields.io/github/license/KhushrajRathod/Finity">
<img alt="version" src="https://img.shields.io/github/v/release/KhushrajRathod/Finity">
</p>

<b><a href="https://github.com/KhushrajRathod/Finity">View on GitHub</a></b> -- <b><a href="https://deno.land/x/finity">View on deno.land</a></b>

- Description: A finite state machine library with a friendly configuration DSL.
- Original module: [finity](https://www.npmjs.com/package/finity)

# Repacks

## ee-ts

<p>
<img alt="build status" src="https://img.shields.io/github/workflow/status/KhushrajRathod/ee-ts/Deno?label=checks" >
<img alt="language" src="https://img.shields.io/github/languages/top/KhushrajRathod/ee-ts" >
<img alt="code size" src="https://img.shields.io/github/languages/code-size/KhushrajRathod/ee-ts">
<img alt="issues" src="https://img.shields.io/github/issues/KhushrajRathod/ee-ts" >
<img alt="license" src="https://img.shields.io/github/license/KhushrajRathod/ee-ts">
<img alt="version" src="https://img.shields.io/github/v/release/KhushrajRathod/ee-ts">
</p>

<b><a href="https://github.com/KhushrajRathod/ee-ts">View on GitHub</a></b> -- <b><a href="https://deno.land/x/ee_ts">View on deno.land</a></b>

- Description: Type-safe event emitters
- Original module: [ee-ts](https://www.npmjs.com/package/ee-ts)