# Diving deep into the Panama Papers

# Abstract
The Panama Papers are leaked documents that detail the internal operations of one of the world's biggest firms in incorporation of offshore entities, Mossack Fonseca. This Panamanian law firm and corporate service provider had financial and attorney-client information for more than 210 000 offshore entities revealed to the public. While offshore business entities are legal, reporters found that some of the Mossack Fonseca shell corporations were used for illegal purposes, namely fraud, tax evasion, and evading international sanctions.
Therefore one may argue that it is of public and state interest to explore the Panama Papers in order to extract insights about the Key Players involved. To do so we will resort to the ICIJ Offshore Leaks Database.  
We intend to present key figures about the evolution of Mossack Fonseca's clients at different scales over the span of 40 years. Moreover we will link our findings to the economy, laws and policies ecountered by the Key Actors. Finally we will conduct a network analysis of the Panama Papers database to better understand its structure.

# Research questions
- What are the key figures about the evolution of Mossack Fonseca's clients at different scales over the span of 40 years ? How can we put these figures into historical (economy, laws, policies...) context ?
- Is there a link between economic and financial indicators and the involvement of a country ? That is what are the main correlates of evasion ?
- What are the additional insights we may extract from a network analysis of the Panama Papers ? What about a specific country analysis ?  
See last section for more information
  
# Dataset
We will use the ICIJ Offshore Leaks Panama Papers Dataset found at: https://www.occrp.org/en/panamapapers/database  
The dataset has been made available as CSV files.  
We will also resort to additional data sources about countries economy, laws and policies for the last 50 years.

# A list of internal milestones up until project milestone 2

Load Dataset-Done  
Preliminary Data inspection-Done  
Preliminary Data transformation-Done  
Enitity key figures-Done  
Intermediary key figures-Done  
Officer key figures-Done  
Nodes population relationship-Done  
Put key figures into historical context-Done  
Load Dataset as a Network-Done    
What's next for Milestone 3 (i.e network analysis, specific country analysis, correlates of evasion)-Done

# What's next for milestone 3

Methods and concepts will be explained in depth as we perform the upcoming tasks. We will mainly perform social network analysis tasks. Here is a non exhaustive list of what to expect:  
  
Regarding network analysis:
- Compute network nodes and edges statistics, distributions. For instance degrees distribution, centrality measures, betweenness measures, page rank and much more 
- Extract and visualize top communities based on modularity measures (Gephi Force Atlas 2 viz ?)
- Investigate possible applications of ML  
- Perform a specific country analysis (most likely Switzerland)  
  
This will help to answer questions such as:  
- Does the degree distribution follow a power law ? 
- What are the "key" nodes (centrality, betweenness, rank) ?
- Is the panama papers network a small world ? 
- What is the shape of the network and what does this tell us about the actors ?
  
Regarding correlates of evasion:  
Basically we want to extract economic and financial indicators (GDP, Financial Secrecy Index...) for each country found in the dataset then check whether these measures are good predictors (or not) of the involvement of a country in the papers.
