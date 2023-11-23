# LSE DS105A (2023/24) - Week 08: Preprocessing and grouping data with pandas, a groupby-apply tutorial

<figure>
    <img src="./figures/DS105L_favicon.png" alt="Image Created with Stable Diffusion"  role="presentation" style="object-fit: cover;width:5em;height:5em;border-radius: 50%;">
    <figcaption>
        <span style="display:inline-block;font-size:0.3em;width:30%;">
        </span>
    </figcaption>

</figure>
<br/>
<br/>

This simple repository contains code and data used in Week 08 of 2023's edition of [DS105A](https://lse-dsi.github.io/DS105/).


# 📚 Preparation

If you want to replicate the analysis in this notebook, you will need to:

1. Clone this repository to your computer.
2. Add it to your VS Code workspace.
3. Go to [IMDb Non-Commercial Datasets](https://developer.imdb.com/non-commercial-datasets/) page and download all `tsv.gz` files from there, place all of that under the `data/raw/` folder. This folder is gitignored, we don't want to push large data files to GitHub!
4. Set up your conda environment:

    ```bash
    conda create -n venv-ds105a python=3.11 ipython
    conda activte venv-ds105a
    ```
5. Make sure `pip` is installed inside that environment:

    ```bash
    conda install pip
    ```

6. Now use that pip to install the packages:

    ```bash
    python -m pip install -r requirements.txt
    ```
5. Open the notebook and run the cells!