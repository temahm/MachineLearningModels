# ML-Models
Different Machine Learning Models and when/how to use each


| Model / Method                        | Best fit                                                  | Real-life examples                                                                      |
| ------------------------------------- | --------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| **TFT / Temporal Fusion Transformer** | Multi-horizon time-series forecasting with many variables | Energy demand forecasting, production demand, patient census forecasting                |
| **XGBoost**                           | High-accuracy tabular prediction                          | Manufacturing defect prediction, credit/fraud scoring, churn, energy failure prediction |
| **KNN**                               | Simple similarity-based classification/regression         | Similar machine-state lookup, patient similarity, recommendation prototypes             |
| **Reinforcement Learning**            | Sequential decisions with rewards                         | Energy optimization, robotic control, dynamic scheduling                                |
| **Logistic Regression**               | Interpretable binary classification                       | Readmission risk, pass/fail quality checks, approval/denial models                      |
| **Polynomial Regression**             | Curved numeric relationships                              | Energy load vs. temperature, process yield curves                                       |
| **Decision Trees**                    | Explainable rule-based prediction                         | Maintenance triage, clinical decision support, operational policies                     |
| **SVM**                               | Small/medium datasets with clear margins                  | Fault classification, medical image/tabular classification                              |
| **Mahalanobis Distance**              | Correlation-aware anomaly detection                       | Fraud, abnormal sensor states, multivariate process control                             |
| **Matrix Profile**                    | Time-series pattern discovery/anomaly detection           | Machine vibration anomaly, energy usage motifs, ICU waveform anomalies                  |
| **Modified Z-Score / MAD**            | Simple robust anomaly detection                           | Sensor spikes, noisy KPI monitoring                                                     |
| **Isolation Forest**                  | Fast tabular anomaly detection                            | Cybersecurity logs, manufacturing process anomalies                                     |
| **One-Class SVM**                     | Boundary around “normal” data                             | Quality inspection when only normal data exists                                         |
| **LOF**                               | Local density anomalies                                   | Clustered customer behavior, grouped machine behavior                                   |
| **Autoencoder**                       | Complex nonlinear anomaly detection                       | Logs, sensors, images, high-dimensional industrial data                                 |



Start with Logistic Regression or Decision Tree for interpretability.
Then test XGBoost for performance.
Use Isolation Forest, MAD, or Mahalanobis Distance for anomaly detection.
Use Matrix Profile when the anomaly is temporal/pattern-based.
Use TFT when you need serious forecasting.
Use Reinforcement Learning only when the problem is about optimizing actions over time.
