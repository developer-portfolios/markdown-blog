# Markdown Blog Posts Template

Demo website: [Zhang Jian's Blog](https://zhangjian.dev).

## Markdown files

- This repository is where you write your blog, using your favorite **Markdown** and **Git**.
- Please keep this repository `public` and **do not** rename it. Also, we only sync changes from the `main` branch.
- The *Markdown files* **only** in the [/drafts](/drafts) and [/published](/published) directories will be **synchronized** to your blog as **posts**.

    - To trigger the synchronization, you need to create your *GitHub App* and install it on this repository. Please read [is-bio GitHub_App.md](https://github.com/is-bio/is-bio/blob/main/docs/GitHub_App.md).
	- After completing the previous step, you should be able to see the contents of the Markdown files displayed in your blog as *posts* when you `git push`. 

- Posts in the [/drafts](/drafts) directory are private and **only visible to you** on the blog.
- Please read [published/README.md](/published/README.md) to learn more.

## Images

Files in the `jpg jpeg gif png` format in the [/images](/images) directory will be synchronized to the `/public/images` directory on the blog server.

## Files

Any file format in the [/files](/files) directory will be synchronized to the `/public/files` directory on the blog server and can be referenced and downloaded in the blog.

## Learn more

Please read [published/README.md](/published/README.md) to learn more.
