# Semantic Prosody Study Kit

A single-page, no-build study kit for corpus research on semantic prosody.

- **Part I: Concepts.** A visual primer on Sinclair (1991), *Corpus, Concordance, Collocation*, leading from the three Cs to the layers of an extended unit of meaning.
- **Part II: Toolkit.** Fillable worksheets for corpus selection, query and extraction settings, a codebook, a coding sandbox with Cohen's kappa, and a reporting checklist.

Everything lives in one file, `index.html`. There is no build step and no dependency beyond web fonts loaded from Google Fonts.

## Run locally

Open `index.html` in any modern browser.

## Publish with GitHub Pages

1. Put `index.html` (and this README) at the root of a repository.
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select your main branch and the `/ (root)` folder, and save.
4. After a minute or two the site is available at `https://<username>.github.io/<repository>/`.

## Your data

- Worksheet entries, checklists, and coding rows are saved in the visitor's own browser (localStorage), on that device only. Nothing is sent to a server.
- Use the export buttons at the end of Section 10 to download the worksheet as Markdown and the coding sheet as CSV. Commit those files yourself if you want them versioned.
- Because storage is per browser, each visitor to a published site sees their own blank worksheet, not yours.

## Licence and data note

**Corpus text.** Many corpora restrict copying and redistributing their text. Before committing concordance lines, exports, or screenshots to a public repository, check the licence of every corpus you used. If redistribution is not permitted, share document IDs, offsets or line numbers, and your codes instead of the text itself.

**Constructed examples.** The concordance lines and demo rows in the page are constructed for teaching. They are not drawn from any corpus.

**This repository.** Add a licence for your own code and written content before making the repository public, so others know how they may reuse it. For example, a permissive software licence such as MIT for the code, and a Creative Commons licence such as CC BY 4.0 for the written material. Choose what suits your situation, and record it here:

> Licence: _(add your choice and a `LICENSE` file)_

**Fonts.** Fraunces, Inter, and JetBrains Mono are loaded from Google Fonts. They are distributed under the SIL Open Font License.

## Citing sources

The reading list and the examples in the page are a starting overview. Verify every citation, quotation, and page number against your own copies of the sources before using them in academic work.
