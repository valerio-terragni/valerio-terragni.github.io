---
layout: page
title: Test Flakiness
description: 
img: /assets/img/flaky.jpg
---

Intermittent test failures (test flakiness) is common during continuous integration as modern software systems have become inherently non-deterministic.
Understanding the root cause of test flakiness is crucial as intermittent test failures might be the result of real non-deterministic defects in the production code, rather than mere errors in the test code.
Given a flaky test, existing techniques for root causing test flakiness compare the runtime behavior of its passing and failing executions.
They achieve this by repetitively executing the flaky test on an instrumented version of the system under test. 
This approach has two fundamental limitations: (i) code instrumentation might prevent the manifestation of test flakiness; (ii) when test flakiness is rare passively re-executing a test many times might be inadequate to trigger intermittent test outcomes.
To address these limitations, we proposed a new idea for root causing test flakiness that actively explores the non-deterministic space without instrumenting code.

Our research proposal won the 2019 Facebook Testing Research Award!

<div class="img_row">
    <img class="col three left" src="{{ site.baseurl }}/assets/img/flaky.png"/>
</div>


Currently I am working along the research direction of the proposal.

Related publications: {% cite terragni-icse-2020 %}

{% bibliography --cited %}