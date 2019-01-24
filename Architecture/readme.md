# Bitcoin Cake

Q: What is Bitcoin Cake?
A: An open source reference model describing layers in the bitcoin network.

As a community we often talk about how bitcoin will scale in layers. The Lightning Network provides a flagship example of of how securely moving transactions off chain gives a performance can lead to huge performance increases.  

Given the decentralised nature of Bitcoin however, it can be difficult to understand how many different layers may be required as the protocol and industry matures.  By understanding the purpose of these layers, the trades offs and benefits at each layer and how people will interact with the different layers, we can begin to better evaluate current centralised services, compare protocols developments and understand how the future may evolve.

Bitcoin cake is a simple layered framework, used as a mental model to evaluate products, services and businesses in the bitcoin ecosystem. 

---

## The Bitcoin Cake

Like any good cake, Bitcoin Cake has layers, five logical layers to be precise.

![Bitcoin Cake Model](https://github.com/karma-pete/Bitcoin-Cake/blob/master/Architecture/bitcoin-cake.jpg "the Bitcoin Cake")

These layers are logical not technical separation to form a full Money over IP (MoIP) stack.

* **Layer 1 Security:** Ensures money is held securely by specific entities. This is best defined by the question "Can someone else take my money?"
* **Layer 2 Transport:** Ensure money can be moved with least possible friction between entities. This is defined by the question "how easily can I move money?"
* **Layer 3 Orchestration:** Orchestrates movement of money based on rules being satisfied. Defined by the question "Can I automate that transaction?"
* **Layer 4 Markets:** Abstracts the movement of money between entities into a market in which value can accrue. Defined by the question “Where does value accrue?”
* **Layer 5 Interface:** Presentation of services to users for interaction. Defined by the question "What is the user experience?"

*More details will be added soon.

Each layer is then evaluated on two axis of trust and risk.  

* **Risk:** Risk is the core factor which separates out our logical layers for instance we may be more likely to accept additional risk in our user interface as long as we know our savings our secure at layer 1. 
* **Trust:** At each layer the purpose can be achieved by solutions on a sliding scale of trust between centralised and decentralised services.  As such trust is played out in the x-axis of our cake.  For example lightning network provides trust minimised transport of bitcoin, whereas does Coinbase achieves similar transport scaling through a central custodial model.

Underpinning this model are the following principle:

* **Risk vs. Function:** We recognise a trade-off between risk and function i.e. simpler functionality leads to less risk of error. In order to increase the level of functionality more risk needs to be accepted. As such we segregate higher level functions from base layer monetary policy.
* **Secure down:** In order to effectively layer an architecture, each layer should be anchored to the one below and inherit its security, borrowing the key feature of the layer below. E.g Lightning Network inherits security by locking bitcoin on the main chain.
* **Properties are emergent:** We recognise that properties are emergent in complex systems.  As such we expect properties to be improved as they are layered as opposed to specifically coded.  For example: there is no privacy layer in this model it is instead emergent across the use of trustless layers. 
* **Trust vs. Risk:** We recognise that trust is not risk. Risk exists in both centralised and distributed institutions.  The critical difference is which party manages that risk and what leverage / influence they will gain from this. 

The purpose of this model then is to allow us to visualise the and understand the correct layering of trust for the level of risk we are accepting.  This will be better explained through examples so I propose to begin working through the following use cases:

* Will Granny use Bitcoin? An exploration of Crypto Banks.
* Etheruem versus Bitcoin and a case for focus.
* What the f**k is a token on Bitcoin and where they fit.
* …Suggestions welcome?

Please consider this a work in progress, subject to updates and contributions and commets are welcome. 

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
