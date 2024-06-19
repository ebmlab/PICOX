# PicoExtractor

This project aims to identify PICO entities from RCT publications. Jupyter Notebook is needed `pip install jupyterlab` (see https://jupyter.org/install for details). The root directory contains source files of the pipeline and a folder containing datasets used in the study. The pipeline starts with preprocessing that converts bioc format to jsonl. Next, the boundary detector and span classifier modules are trained. After training, the model can be used for inference, see source files. At last, an example of usage is provided. 

Before running the pipeline, please create a `data` folder under the root and set up the folder to keep input files (including both raw and processed data) and model checkpoints. Please read the beginning of each source file as an example.

This project is released under MIT license. Please feel free to cite "A span-based model for extracting overlapping PICO entities from randomized controlled trial publications" (https://pubmed.ncbi.nlm.nih.gov/38471120/) if you find this project helpful.

>Copyright 2024 WengLab
>
>Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
>
>The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
>
>THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.`
