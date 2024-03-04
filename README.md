We present ProVerif automated security verification codes tailored for "Untraceable Blockchain-assisted Authentication and Key Exchange in Medical
Consortiums." 

The repository includes three distinct codes designed to test the authentication and key agreement protocol against various attacks. Additionally, it evaluates whether the protocol provides perfect forward secrecy.

Codes and Testing Scenarios:
    Testing Common Attacks (common.pv)
        This code assesses the authentication and key agreement protocol's resilience against common attacks in a smart grid context.
    Testing Ephemeral Secret Leakage (ESL) Attack (KSSTIA.pv)
        Focusing on ephemeral secret leakage, this code examines the protocol's resistance to potential threats in this area.
    Testing Perfect Forward Secrecy (PFS) (PFS.pv)
        This code is dedicated to testing and verifying the protocol's adherence to the perfect forward secrecy property.

Obtaining Results:
To obtain results for these tests, simply copy and paste the respective code into the ProVerif tool available at http://proverif20.paris.inria.fr/ and run them separately.
Feel free to explore, contribute, and enhance the security verification process for key management protocols in smart grids with ProVerif. We appreciate your interest and collaboration!
