Traffic congestion warning system based on regression analysis and memory network

* In the project, we propose a short-term off-site traffic flow prediction model based on support vector regression and long short-term memory networks, combined with fuzzy synthetic evaluation method, a traffic congestion early warning system is constructed. 
* By learning the historical traffic flow data of the upstream road section, the support vector machine regression prediction model, which has been optimized by the particle swarm optimization algorithm, can accurately estimate the average road speed and traffic flow of the upstream road section in the future. Combined with prediction results and historical data, long short-term memory networks can accurately estimate the average road speed and traffic flow of downstream road sections. The final forecast data is transformed into traffic parameters to obtain an evaluation index set including average speed, traffic flow density, and road saturation. The weights of the evaluating indicators under the morning peak, evening peak and other periods are determined by the entropy method and using the membership function to determine the evaluation matrix of each indicator. Finally, the road traffic congestion level is obtained according to the principle of maximum membership degree. Once the threshold is reached, an alarm is issued. 
* Numerical experiments are performed using the data from the No.2552 and No.2554 highway in the Caltrans Performance Measurement System of California, USA, where No.2554 is upstream and No. 2552 is downstream. The results show that the system has great performance and the prediction accuracy can reach 96%. 



