circulating liquid, which is then cooled and reused. By focusing cooling at the source of heat, this method ensures precise thermal control, reduces dependency on traditional air-cooling systems, and is well-suited for high-performance computing (HPC) and AI applications. The service cycle for this method is shorter, given the hardware constraint. Hence it is not widely adopted.

Efficiency of different Liquid cooling systems

<table><thead><tr><th>Technology</th><th>Cooling efficiency</th><th>Deployment time</th><th>Energy consumption</th><th>CapEx/OpEx</th><th>Scalability</th><th>Sustainability</th><th>Use cases</th></tr></thead><tbody><tr><td>LIC</td><td>Very high (COP >10)</td><td>Long</td><td>Very low (PUE approx. 1.05–1.2)</td><td>High/Low</td><td>Moderate</td><td>Very High</td><td>Useful where there is high dissipation of heat, especially where high-performance computing, dense server setups, AI processing etc.</td></tr><tr><td>DCLC</td><td>High (COP approx. 8-10)</td><td>Moderate</td><td>Low</td><td>Medium-High</td><td>High</td><td>High</td><td></td></tr><tr><td>Direct-to-chip</td><td>Very high</td><td>Moderate</td><td>Very low</td><td>Medium</td><td>High</td><td>High</td><td></td></tr></tbody></table>

Source: Compute Project (OCP) - Technical standards and community-sourced designs

### 2.1.3.3 Cooling techniques employed in data centers in India

In India, data centers employ a variety of cooling techniques to address the challenges posed by increasing computational demands, high ambient temperatures, and sustainability goals. The selection of cooling methods is influenced by factors such as energy efficiency, scalability, and environmental considerations.³¹

i. **Traditional air-based cooling systems:** Computer Room Air Conditioning (CRAC) and Computer Room Air Handler (CRAH) units are widely used in Indian data centers. These systems are favored for their reliability and ease of integration into existing infrastructures. CRAC units use refrigerants to cool the air, while CRAH systems utilize chilled water circulated through cooling coils. Both methods are effective for moderate-density server environments and are relatively straightforward to deploy and maintain.

ii. **In-row cooling:** In-row cooling systems are increasingly adopted in India, especially in modular and scalable data center designs. By placing cooling units directly between server racks, these systems provide targeted cooling, reducing energy consumption and improving efficiency. This approach is particularly beneficial in high-density setups where precise temperature control is essential.

iii. **Liquid cooling technologies:** With the rise of High Performance Computing (HPC) and Artificial Intelligence (AI) workloads, liquid cooling methods are gaining traction in India. Techniques such as Liquid Immersion Cooling (LIC) and Direct-to-Chip Cooling offer superior cooling efficiency and are capable of handling higher heat densities.

iv. **Evaporative cooling:** In regions with suitable climatic conditions, evaporative cooling is employed as an energy-efficient cooling solution. This method leverages the natural process of water evaporation to lower air temperatures, thereby reducing the reliance on mechanical refrigeration and decreasing overall energy consumption.

### 2.1.3.4 Heat reuse and waste energy management prevalent for data centers in India

Heat reuse in Indian data centers remains at a nascent stage but is steadily gaining momentum as a strategy to enhance energy efficiency and drive sustainability goals. International case studies, such as Fortum's successful implementation in Finland, demonstrates the significant potential of this approach. However, large-scale adoption in India is constrained by key challenges like high upfront capital expenditure and a limited concentration of proximate heat off-takers. Strategic policy intervention and incentive mechanisms will be critical to overcoming these barriers and enabling scalable heat reuse as the data center sector continues its rapid expansion. To enhance cooling efficiency, specifically in high density environments, rear door heat exchanger (RDHx) is used in data centers. A RDHx is a passive or active cooling device mounted on the rear of a server rack that removes heat from the exhaust air of IT equipment before it enters the data center environment.