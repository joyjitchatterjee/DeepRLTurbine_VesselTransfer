# DeepRLTurbineVesselTransfer
Supplementary material for our paper "Deep Reinforcement Learning for Maintenance Planning of Offshore Vessel Transfer" in submission to RENEW 2020, Lisbon, Portugal.

Initially, SMOTE can be performed using the appropriate script. And as the second step, utilise the fault prediction using XGBoost with SHAP game theory approach to predict fault types. Finally, utilise the simulated RL enviornment in the grip map based on the Taxi OpenAI Gym and train the RL algorithms of your choice.

Refer to https://youtu.be/ss02F5vwojM for a short video demonstrating text-based simulation of offshore vessel transfer planning and decision making.

Note: This study uses a hypothetical envioronment for learning process during reinforcement learning's policy updates, so the rewards and reward function may perform differently under varying circumstances of fault types predicted by XGBoost and maintenance actions mapped to priorites in the scale of 0-4.
Special acknowledgment: ORE Catapult for providing us insights from the LDT's data.
