Have a look at this binary addition:
![](.guides/img/gridb.png)

We are adding 8-bit numbers and this has caused a problem. All eight bits have been used and the 1 that was carried over in the last column has nowhere to go – it has been **carried out**. Therefore the result of the calculation would be wrong!

This is called an **overflow error**.

This condition occurs when a calculation produces a result that is greater than the computer can deal with or store.
When this occurs, the microprocessor is informed that an error has occurred

Overflow errors have led to many real-life disasters.

![](.guides/img/ariane.png)

The most famous disaster caused by an overflow error was the crash of the Ariane 5 space rocket launched by the European Space Agency in 1996.
Data about velocity was stored in 16-bit variable. This had been fine for the Ariane 4 but the 5 model was much faster and the value overflowed. This one error set of a chain of events leading to self-destruction.

They should have carried out a range check when testing the software!

Others include the failure of the Patriot missile defence system in 1991 and it is claimed that the Boeing 787 aircraft’s engines could shut down in flight due to a similar problem.

Have a look at these websites:
[http://www.cambridgedigital.com/mooc/html/phase2/33/33_Starter_Activity.html](http://www.cambridgedigital.com/mooc/html/phase2/33/33_Starter_Activity.html)

[http://www.cambridgedigital.com/mooc/html/jan14/33_Activity1/33_Activity1.html](http://www.cambridgedigital.com/mooc/html/jan14/33_Activity1/33_Activity1.html)