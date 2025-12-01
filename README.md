# Comparing Consignment Stock Models in Supply Chains

This repository contains the Python code  for a study comparing four consignment stock (CS)–based inventory models in a vendor–buyer supply chain.

The analysis starts from the baseline consignment stock model of Braglia & Zavanella (2003) and examines how three extensions modify the cost structure and optimal policy:

1. **Baseline CS model (with and without delayed deliveries)**  
2. **Cost-structure CS–k model (Huang & Chen, 2009)**  
3. **Obsolescence CS model (Persona et al., 2007)**  
4. **Multi-buyer CS model (Zavanella & Zanoni, 2009)**  

All models are implemented under a common set of base-case parameters and evaluated using simple grid searches over the relevant integer decision variables.
