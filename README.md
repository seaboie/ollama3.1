<a id="readme-top"></a>


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="">
    <img src="https://raw.githubusercontent.com/seaboie/images/main/images/logoTransparent.png" alt="Logo" width="120" height="120">
  </a>

  <h3 align="center">Ollama</h3>

  <p align="center">
    Create your own Custom LLM Agent Using Open Source Models (llama3.1)
    <br />
    <a href="https://dev.to/emmakodes_/create-your-own-custom-llm-agent-using-open-source-models-llama31-4aag"><strong>On website »</strong></a>
    <br />
    
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#activate-virtual-environment">activate Virtual environment</a></li>
      </ul>
    </li>
    <li><a href="#general">General</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>




<!-- GETTING STARTED -->
## Getting Started

### Installation
Follow the instructions based on your OS type in its GitHub README to install Ollama:  
```bash
https://github.com/ollama/ollama
```  

### activate Virtual environment  

```bash
python3 -m venv .venv
```  
```bash
source .venv/bin/activate
```  


<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- General -->
## General  

- List all `ollama` models on my computer  

```bash
ollama list
```  

- Display description of `llama3.1`  

```bash
ollama show llama3.1
```  

<!-- USAGE EXAMPLES -->
## Usage

- Run server  

```bash
ollama serve
```  

- Run model

> `llama3.1`

```bash
ollama run llama3.1
```  

> `llava` can watch Image too  

```bash
ollama run llava
```  

- Stop server

```bash
pkill ollama
```  


<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments  

* [Create your own Custom LLM Agent Using Open Source Models (llama3.1)](https://dev.to/emmakodes_/create-your-own-custom-llm-agent-using-open-source-models-llama31-4aag)  
* [Ollama on github](https://github.com/ollama/ollama)  
* [ollama.com/library](https://ollama.com/library)  



<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[logo-image]:https://raw.githubusercontent.com/seaboie/images/main/images/logoTransparent.png

