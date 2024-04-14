# Text Classification Based on Chinese Dataset THUCNEWs
This is a classification example based on the THUCNEWs dataset and using a very simple model.

## Some dependencies
- python == 3.8.12
- tensorflow == 2.9.0
- jieba == 0.42.1
- tqdm == 4.63.1

## Dataset
THUCNEWs: http://thuctc.thunlp.org/
(Recommendation: This dataset is larger, use a subset of this dataset if running locally.)<br />
HIT stop word dataset: (I'm sorry, I didn't find the official release page for this dataset, if you know, please tell me where it is.)

## Run
If you know how to use jupyter, I'm sure you'll be able to run it.

## Known Issues
- **Question-1**:<br />
    IOPub data rate exceeded.<br />
    The notebook server will temporarily stop sending output to the client in order to avoid crashing it.<br />
    To change this limit, set the config variable<br />
    `--NotebookApp.iopub_data_rate_limit`.<br />
    Current values:<br />
    NotebookApp.iopub_data_rate_limit=1000000.0 (bytes/sec)<br />
    NotebookApp.rate_limit_window=3.0 (secs)<br /><br />
        
You can try to run the following command to run the notebook:<br />
**SOLUTION1**: `jupyter lab --NotebookApp.iopub_data_rate_limit=1.0e10`<br />
**SOLUTION2**: `jupyter notebook --NotebookApp.iopub_data_rate_limit=1.0e10`<br />

## References
[1] Maosong Sun, Jingyang Li, Zhipeng Guo, et al. THUCTC: An Efficient Chinese Text Classifier. 2016.<br />
[2] Harbin Institute of Technology stop word dataset.
