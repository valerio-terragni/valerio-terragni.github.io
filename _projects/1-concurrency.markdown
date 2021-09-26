---
layout: page
title: Testing and Analysis of Concurrent Programs
description: 
img: /assets/img/cpu-wall.jpg
---

Multi-core processors are now pervasive, spanning from embedded systems and mobile devices, to PCs, all the way to high-end servers and distributed systems. To unleash the computing power of multi-core processors, developers have to write concurrent (multi-threaded) programs. However, writing correct and efficient concurrent programs is difficult and error-prone. 

An effective approach to verify the correctness of object-oriented concurrent classes consists of automatically generating concurrent tests and checking if they exhibit concurrency failures by exploring their interleaving spaces. A concurrent test consists of multiple concurrently executing threads that exercise the public interface of a class under test. The high cost of exploring interleaving spaces poses great challenges when generating concurrent tests.


<div class="img_row">
    <img class="col three left" src="{{ site.baseurl }}/assets/img/test-gen-concurrency1.png"/>
</div>


During my PhD and Post-doc I proposed new techniques to effectively generate concurrent tests. Currently, I am working on fruther improve the effectiveness of concurrent test generators.

Related publications: {% cite terragni-icst-2019 terragni-ase-2018 bianchi-fse-2017 terragni-icse-2016 terragni-icse-2015 %}

{% bibliography --cited %}
 
