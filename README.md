Gradio   :  http://127.0.0.1:7860

# AI Task Management System
Automates task categorization, priority prediction, and team workload balancing for project management.

# Features

1. Task Classification: ML-based category detection from text descriptions
2. Priority Prediction: XGBoost model estimates task importance
3. Smart Assignment: Auto-assigns tasks based on capacity and skills

# Prerequisites

Required model files 
- `svm_model.pkl`
- `tfidf_vectorizer.pkl` 
- `xgb_priority_model.pkl`
- `priority_scaler.pkl`
- `priority_target_encoder.pkl`
- `priority_label_encoders.pkl`
- `priority_feature_cols.pkl`

 # Tabs
Classify: Enter task description to predict category (Development, Testing, Design, Documentation, Research, Meeting)
Priority: Set complexity, urgency, hours, category, status, department to get priority level
Assign: Enter task details and assign to specific team member or use Auto-Assign for optimal allocation based on current workload and skills


 # Team Data
System uses embedded team dataset with  members and their current assigned tasks and skill sets.
