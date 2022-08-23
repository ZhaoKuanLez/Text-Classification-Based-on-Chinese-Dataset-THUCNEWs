# Text Classification Based on Chinese Dataset THUCNEWs
This is a classification example based on the THUCNEWs dataset and using a very simple model, because it was my homework before, hahaha, so it provides a basic idea of Chinese text classification, I hope you can refer to its production Produce your own excellent model.

## Some dependencies
- Python == 3.8.12
- Tensorflow == 2.9.0
- jieba == 0.42.1
- tqdm == 4.63.1

## Dataset
THUCNEWs: http://thuctc.thunlp.org/
(Recommendation: This dataset is larger, use a subset of this dataset if running locally.)

## Run
If you know how to use jupyter, I'm sure you'll be able to run it.

## Known Issues
- **Question-1**:<br />
        IOPub data rate exceeded.<br />
        The notebook server will temporarily stop sending output<br />
        to the client in order to avoid crashing it.<br />
        To change this limit, set the config variable<br />
        `--NotebookApp.iopub_data_rate_limit`.<br />
        Current values:<br />
        NotebookApp.iopub_data_rate_limit=1000000.0 (bytes/sec)<br />
        NotebookApp.rate_limit_window=3.0 (secs)<br /><br />
        
You can try to run the following command to run the notebook:<br />
**SOLUTION1**: `jupyter lab --NotebookApp.iopub_data_rate_limit=1.0e10`<br />
**SOLUTION2**: `jupyter notebook --NotebookApp.iopub_data_rate_limit=1.0e10`<br />

## References
[1] Maosong Sun, Jingyang Li, Zhipeng Guo, Yu Zhao, Yabin Zheng, Xiance Si, Zhiyuan Liu. THUCTC: An Efficient Chinese Text Classifier. 2016.
