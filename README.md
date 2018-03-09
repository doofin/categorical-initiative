# categorical-initiative
An collaborative learning group to tackle category theory

# why

I spend countless time to learn category theory ,while I still feel that I don't really understand it.I think the only way to actually 'grasp' it is by formalizing it via a programming language.


# Requirement
Experience in functional programming is mandated (Haskell etc.).
Product,coproduct in category theory

# How and which language

Dependent type is powerful enough to construct category theory.Agda is one of them,and it also has HoTT formalized.So Agda would be the language of choice.

The higher inductive type in HoTT seems very graceful and convenient,but the support of it is yet to be completed.Keep track of Cubical type theory if you are interested.We are adopting a more traditional approach of defining these as record.


# Resources
 https://github.com/agda/agda-stdlib/blob/master/src/Algebra.agda and
 
 https://github.com/agda/agda-stdlib/blob/master/src/Algebra/Structures.agda . Check here for how to define algebraic structures as record.Record in agda and idris are like module.
