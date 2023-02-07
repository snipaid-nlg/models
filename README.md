# models
## LLMs for NLG in German

This repository provides an comprehensive overview of available large language models (LLM) for natural language generation (NLG) in German.

<table>
    <tr>
        <td>
            <p>Name</p>
        </td>
        <td>
            <p>Size</p>
        </td>
        <td>
            <p>Model Card</p>
        </td>
        <td>
            <p>License</p>
        </td>
        <td>
            <p>Implementation</p>
        </td>
        <td>
            <p>Paper</p>
        </td>
    </tr>
    <tr>
        <td>
            <p>GPT-J</p>
        </td>
        <td>
            <p>6B</p>
        </td>
        <td>
            <p><a href="https://huggingface.co/EleutherAI/gpt-j-6B">EleutherAI/gpt-j-6B</a></p>
        </td>
        <td>
            <p>MIT, Weights: Apache 2.0</p>
        </td>
        <td>
            <p><a
                    href="https://github.com/kingoflolz/mesh-transformer-jax/">https://github.com/kingoflolz/mesh-transformer-jax/</a>
            </p>
        </td>
        <td>
            <p>-</p>
        </td>
    </tr>
    <tr>
        <td>
            <p>BLOOMZ</p>
        </td>
        <td>
            <p>560M</p>
            <p>1.1B</p>
            <p>1.7B</p>
            <p>3B</p>
            <p>7.1B</p>
            <p>176B</p>
        </td>
        <td>
            <p><a href="https://huggingface.co/bigscience/bloomz-560m">bigscience/bloomz-560m</a></p>
            <p><a href="https://huggingface.co/bigscience/bloomz-1b1">bigscience/bloomz-1b1</a></p>
            <p><a href="https://huggingface.co/bigscience/bloomz-1b7">bigscience/bloomz-1b7</a></p>
            <p><a href="https://huggingface.co/bigscience/bloomz-3b">bigscience/bloomz-3b</a></p>
            <p><a href="https://huggingface.co/bigscience/bloomz-7b1">bigscience/bloomz-7b1</a></p>
            <p><a href="https://huggingface.co/bigscience/bloomz">bigsience/bloomz</a></p>
        </td>
        <td>
            <p>RAIL</p>
        </td>
        <td>
            <p><a href="https://github.com/bigscience-workshop/xmtf">https://github.com/bigscience-workshop/xmtf</a>
            </p>
        </td>
        <td>
            <p>Muennighoff, Niklas, et al. Crosslingual generalization through multitask finetuning. (2022). DOI: <a
                    href="https://doi.org/10.48550/arXiv.2211.01786">https://doi.org/10.48550/arXiv.2211.01786</a>
            </p>
        </td>
    </tr>
    <tr>
        <td>
            <p>BLOOM german</p>
        </td>
        <td>
            <p>350M</p>
            <p>1.5B</p>
            <p>6.4B</p>
        </td>
        <td>
            <p><a href="https://huggingface.co/malteos/bloom-350m-german">malteos/bloom-350m-german</a></p>
            <p><a href="https://huggingface.co/malteos/bloom-1b5-clp-german">malteos/bloom-1b5-clp-german</a></p>
            <p><a href="https://huggingface.co/malteos/bloom-6b4-clp-german">malteos/bloom-6b4-clp-german</a></p>
        </td>
        <td>
            <p>RAIL</p>
        </td>
        <td>
            <p><a href="https://github.com/malteos/clp-transfer">https://github.com/malteos/clp-transfer</a></p>
        </td>
        <td>
            <p>Ostendorff, Malte; Rehm, Georg. Efficient Language Model Training through Cross-Lingual and
                Progressive Transfer Learning. (2023). DOI: https://doi.org/10.48550/arXiv.2301.09626</p>
        </td>
    </tr>
    <tr>
        <td>
            <p>OPT</p>
        </td>
        <td>
            <p>125M</p>
            <p>350M</p>
            <p>1.3B</p>
            <p>2.7B</p>
            <p>6.7B</p>
            <p>13B</p>
            <p>30B</p>
            <p>66B</p>
        </td>
        <td>
            <p><a href="https://huggingface.co/facebook/opt-125m">facebook/opt-125m</a></p>
            <p><a href="https://huggingface.co/facebook/opt-350m">facebook/opt-350m</a></p>
            <p><a href="https://huggingface.co/facebook/opt-1.3b">facebook/opt-1.3b</a></p>
            <p><a href="https://huggingface.co/facebook/opt-2.7b">facebook/opt-2.7b</a></p>
            <p><a href="https://huggingface.co/facebook/opt-6.7b">facebook/opt-6.7b</a></p>
            <p><a href="https://huggingface.co/facebook/opt-13b">facebook/opt-13b</a></p>
            <p><a href="https://huggingface.co/facebook/opt-30b">facebook/opt-30b</a></p>
            <p><a href="https://huggingface.co/facebook/opt-66b">facebook/opt-66b</a></p>
        </td>
        <td>
            <p>OPT-LICENSE</p>
        </td>
        <td>
            <p><a href="https://github.com/facebookresearch/metaseq">https://github.com/facebookresearch/metaseq</a>
            </p>
        </td>
        <td>
            <p>Zhang, Susan, et al. Opt: Open pre-trained transformer language models. (2022). DOI: <a
                    href="https://doi.org/10.48550/arXiv.2205.01068">https://doi.org/10.48550/arXiv.2205.01068</a>
            </p>
        </td>
    </tr>
    <tr>
        <td>
            <p>FLAN-T5</p>
        </td>
        <td>
            <p>80M</p>
            <p>250M</p>
            <p>780M</p>
            <p>3B</p>
            <p>11B</p>
        </td>
        <td>
            <p><a href="https://huggingface.co/google/flan-t5-small">google/flan-t5-small</a></p>
            <p><a href="https://huggingface.co/google/flan-t5-base">google/flan-t5-base</a></p>
            <p><a href="https://huggingface.co/google/flan-t5-large">google/flan-t5-large</a></p>
            <p><a href="https://huggingface.co/google/flan-t5-xl">google/flan-t5-xl</a></p>
            <p><a href="https://huggingface.co/google/flan-t5-xxl">google/flan-t5-xxl</a></p>
        </td>
        <td>
            <p>Apache 2.0</p>
        </td>
        <td>
            <p><a href="https://github.com/google-research/t5x">https://github.com/google-research/t5x</a></p>
        </td>
        <td>
            <p>Chung, Hyung Won, et al. Scaling instruction-finetuned language models. (2022). DOI:
                https://doi.org/10.48550/arXiv.2210.11416</p>
        </td>
    </tr>
    <tr>
        <td>
            <p>MT0</p>
        </td>
        <td>
            <p>300M</p>
            <p>580M</p>
            <p>1.2B</p>
            <p>3.7B</p>
            <p>13B</p>
        </td>
        <td>
            <p><a href="https://huggingface.co/bigscience/mt0-small">bigscience/mt0-small</a></p>
            <p><a href="https://huggingface.co/bigscience/mt0-base">bigscience/mt0-base</a></p>
            <p><a href="https://huggingface.co/bigscience/mt0-large">bigscience/mt0-large</a></p>
            <p><a href="https://huggingface.co/bigscience/mt0-xl">bigscience/mt0-xl</a></p>
            <p><a href="https://huggingface.co/bigscience/mt0-xxl">bigscience/mt0-xxl</a></p>
        </td>
        <td>
            <p>Apache 2.0</p>
        </td>
        <td>
            <p><a href="https://github.com/bigscience-workshop/xmtf">https://github.com/bigscience-workshop/xmtf</a>
            </p>
        </td>
        <td>
            <p>Muennighoff, Niklas, et al. Crosslingual generalization through multitask finetuning. (2022). DOI: <a
                    href="https://doi.org/10.48550/arXiv.2211.01786">https://doi.org/10.48550/arXiv.2211.01786</a>
            </p>
        </td>
    </tr>
    <tr>
        <td>
            <p>GPT2</p>
        </td>
        <td>
            <p>117M</p>
            <p>117M</p>
            <p>1.5B</p>
            <p>?</p>
            <p>?</p>
            <p>?</p>
        </td>
        <td>
            <p><a href="https://huggingface.co/benjamin/gpt2-wechsel-german">benjamin/gpt2-wechsel-german</a></p>
            <p><a
                    href="https://huggingface.co/malteos/gpt2-wechsel-german-ds-meg">malteos/gpt2-wechsel-german-ds-meg</a>
            </p>
            <p><a href="https://huggingface.co/malteos/gpt2-xl-wechsel-german">malteos/gpt2-xl-wechsel-german</a>
            </p>
            <p><a href="https://huggingface.co/benjamin/gerpt2">benjamin/gerpt2</a></p>
            <p><a href="https://huggingface.co/benjamin/gerpt2-large">benjamin/gerpt2-large</a></p>
            <p><a href="https://huggingface.co/dbmdz/german-gpt2">dbmdz/german-gpt2</a></p>
        </td>
        <td>
            <p>MIT</p>
        </td>
        <td>
            <p><a href="https://github.com/CPJKU/wechsel">https://github.com/CPJKU/wechsel</a> <a
                    href="https://github.com/bminixhofer/gerpt2">https://github.com/bminixhofer/gerpt2</a></p>
        </td>
        <td>
            <p>Minixhofer, Benjamin, et al. WECHSEL: Effective initialization of subword embeddings for
                cross-lingual transfer of monolingual language models. (2021). DOI:
                http://dx.doi.org/10.18653/v1/2022.naacl-main.293</p>
        </td>
    </tr>
    <tr>
        <td>
            <p>mGPT</p>
        </td>
        <td>
            <p>1.3B</p>
        </td>
        <td>
            <p><a href="https://huggingface.co/sberbank-ai/mGPT">sberbank-ai/mGPT</a></p>
        </td>
        <td>
            <p>Apache 2.0</p>
        </td>
        <td>
            <p><a href="https://github.com/ai-forever/mgpt">https://github.com/ai-forever/mgpt</a></p>
        </td>
        <td>
            <p>Shliazhko, Oleh, et al. mgpt: Few-shot learners go multilingual. (2022). DOI: <a
                    href="https://doi.org/10.48550/arXiv.2204.07580">https://doi.org/10.48550/arXiv.2204.07580</a>
            </p>
        </td>
    </tr>
    <tr>
        <td>
            <p>MT5</p>
        </td>
        <td>
            <p>300M</p>
            <p>580M</p>
            <p>1.2B</p>
            <p>3.7B</p>
            <p>13B</p>
        </td>
        <td>
            <p><a href="https://huggingface.co/google/mt5-small">google/mt5-small</a></p>
            <p><a href="https://huggingface.co/google/mt5-base">google/mt5-base</a></p>
            <p><a href="https://huggingface.co/google/mt5-large">google/mt5-large</a></p>
            <p><a href="https://huggingface.co/google/mt5-xl">google/mt5-xl</a></p>
            <p><a href="https://huggingface.co/google/mt5-xxl">google/mt5-xxl</a></p>
        </td>
        <td>
            <p>Apache 2.0</p>
        </td>
        <td>
            <p><a href="https://github.com/google-research/multilingual-t5">https://github.com/google-research/multilingual-t5</a></p>
        </td>
        <td>
            <p>Xue, Linting, et al. mT5: A massively multilingual pre-trained text-to-text transformer. (2020). DOI:
                <a href="https://doi.org/10.18653/v1/2021.naacl-main.41">https://doi.org/10.18653/v1/2021.naacl-main.41</a>
            </p>
        </td>
    </tr>
</table>
