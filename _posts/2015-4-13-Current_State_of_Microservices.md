---
layout: post
title: Current State of Microservices 
---
**Microservices** are definitely a paradigm shift in software-architectural thinking. It didn’t happen over night; It stands on the shoulders of all the knowledge and practical experience that was gained over the last few decades, around software architecture, design and operations.
 
Although Compartmentalization is as old and time-tested as it goes (and obviously not just in Software), it’s completely green-fields with regard to implementation in the form of Microservices. Luckily we’re at a time where the idea can be realized in production, without requiring a significant change in the way software is developed. Docker is a great example of that, especially in the sense that it made Compartmentalization accessible to the public. Maybe that’s what was missing in previous attempts. 
There’s no cook-book on how to deploy Microservices at-scale, or in production, or ‘for-real'. People like us, all over the world are trying to figure this out. All this is spawning immense growth, which we’re all a part of.

Let me tell you, there will be some nice scars to show in a few years, and some ideas and technologies won’t make it. This is natural, and it’s exactly what happened with Computer Networking. Who remembers Token Ring?
It’s the fact that many ideas exist, and some will fail that makes the whole field more robust, or Anti-Fragile (thanks Nicolas Nassim Taeb).

It’s absolutely logical to re-examine everything we know at a time like this, and try to push the boundaries of the new concepts and technologies to their limit. For example, how should Microservices discover each other? how should they communicate?

Personally, and I may be wrong, when I think about production and scale, I think about stability. And when it comes to stability, old and time-tested things tend to work well. These ideas have survived for a reason. 
Networking technology is old and time tested. DNS, Proxy technologies, IP, DCHP, TCP etc - are very mature, well documented and defined. I’m not ready to throw them out just yet.
Using existing old, time-tested Networking technology (maybe with a new twist, like Weave) to solve new (or old) problems, seems to me like a very promising path forward.

Time will tell.


(Y)