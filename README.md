# CS598Code-Effiencient-Panoptic-Segmentation
The code is from Panoptic-Segmentation Forecasting, we change the bg model and fg model to implement our idea.
In the fg model, we replace convLSTM to convGRU and in the bg model, we add downsampling function. 
Those are shown in the model\fg\fg_model and model\bg\bg_model. 
