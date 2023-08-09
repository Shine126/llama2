# llama2
llama模型说明

We are unlocking the power of large language models. Our latest version of Llama is now accessible to individuals, creators, researchers and businesses of all sizes so that they can experiment, innovate and scale their ideas responsibly.

This release includes model weights and starting code for pretrained and fine-tuned Llama language models — ranging from 7B to 70B parameters.

This repository is intended as a minimal example to load Llama 2 models and run inference. For more detailed examples leveraging HuggingFace, see llama-recipes.


llama应用顺序，下载-安装-微调

## 1、下载 Download
### （1）下载说明
#### Meta官网下载
⚠️ 7/18: We're aware of people encountering a number of download issues today. Anyone still encountering issues should remove all local files, re-clone the repository, and request a new download link. It's critical to do all of these in case you have local corrupt files. When you receive the email, copy only the link text - it should begin with https://download.llamameta.net and not with https://l.facebook.com, which will give errors.

In order to download the model weights and tokenizer, please visit the Meta AI website and accept our License.

Once your request is approved, you will receive a signed URL over email. Then run the download.sh script, passing the URL provided when prompted to start the download. Make sure that you copy the URL text itself, do not use the 'Copy link address' option when you right click the URL. If the copied URL text starts with: https://download.llamameta.net, you copied it correctly. If the copied URL text starts with: https://l.facebook.com, you copied it the wrong way.

Pre-requisites: make sure you have wget and md5sum installed. Then to run the script: ./download.sh.

Keep in mind that the links expire after 24 hours and a certain amount of downloads. If you start seeing errors such as 403: Forbidden, you can always re-request a link.
#### Hugging Face下载
We are also providing downloads on Hugging Face. You must first request a download from the Meta AI website using the same email address as your Hugging Face account. After doing so, you can request access to any of the models on Hugging Face and within 1-2 days your account will be granted access to all versions.

### （2）注意事项
#### 链接期限

#### 常见错误

## 2、安装 Install
### （1）终端路线 llama.cpp


### （2）webUI路线 llama_webUI


## 3、微调 Finetune