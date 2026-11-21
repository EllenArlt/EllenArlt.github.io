---
title: "Sound State Encodings in Translational Separation Logic Verifiers"
collection: publications
category: conferences
permalink: /publication/SoundStateEncoding
excerpt: 'Automated program verifiers are often organized into a front-end, which encodes an input program into an intermediate verification language (IVL), and a back-end, which proves that the IVL program is correct. Soundness of such translational verifiers requires that the back-end verification is sound and that correctness of the IVL program implies correctness of the input program. Existing formalizations for translational verifiers based on separation logic target the former, but support the latter only under the strong assumption that there exists a separation logic for the input program with the same state model as the IVL. This assumption is unrealistic in practice, especially since the state model also defines the supported separation logic resources.
We present the first formal framework for proving the soundness of translational separation logic verifiers with non-trivial state encodings. To be applicable to various front-ends and IVLs, our framework only assumes the existence of a homomorphic encoding relation between the front-end and IVL state models. At the core of our framework is a novel condition, backward satisfiability, which is crucial to guarantee the soundness of the front-end translation. We formalize our framework for front-end verifiers based on concurrent separation logic and separation logic IVLs, such as Raven, VeriFast, and Viper. We demonstrate its expressiveness by proving soundness for three common state encodings. Our framework and all proofs are formalized in Isabelle/HOL.'
date: 2026-10-05
venue: PACML, presented by Hongyi Ling in OOPSLA
paperurl: 'https://dl.acm.org/doi/epdf/10.1145/3839462'
---

The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font.
