# VeriHybrid

Whenever continuous dynamics and discrete control interact, hybrid systems arise. As hybrid systems become ubiquitous and more and more complex, analysis and synthesis techniques are in high demand to design safe hybrid systems. This is however challenging due to the nature of hybrid systems and their designs, and the question of how to formulate and reason their safety problems. Previous work has demonstrated how to extend discrete modelling language Event-B with continuous supports to integrate traditional refinement in hybrid system design. In the same spirit, we extend previous work by proposing a strategy that can coherently refine an abstract hybrid system design with safety constraints down to a concrete one, integrated with implementable discrete control, that can behave safely. We demonstrate our proposal on a smart heating system that regulates room temperature between two references, and we share our experience.

Repository structure
------

* The real number theory [theory-axiom-real](/theory-axiom-real/)
* The smart heating system case study [ex-heating-maintainer-event](/ex-heating-maintainer-event/)
* The nuclear cooling case study [ex-heating-rod](/ex-heating-rod/)
* The car stop case study [ex-car-stop](/ex-car-stop/)
* The base pattern that can be instaniated on the new case study [ex-base](/ex-base/)

Setup
------
The projects are developed under:
* Rodin v.3.4.
* Theory plugin v.4.0

All proofs are discharged.

The projects are directly importable to reproduce the result.

License
------
This project is licensed under Eclipse Public License (v2). 