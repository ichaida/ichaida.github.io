Simple Remix Blog is a blog template built using [remix.run](https://remix.run/) and [TailwindCSS](https://tailwindcss.com/). It supports markdown and MDX for the blog posts. You can clone it and start your own blog in a few minutes. Check out the documentation below to get started.

## Usage

Once you've cloned the project you have to install the dependencies:

```bash
yarn install
```

and run the `dev` script:

```bash
yarn dev
```

> The blog should now be running on localhost:3000.

Now, you have to update the `app/siteMetadata.js` file witht the updated metadata.

To create a new post you have to add a new markdown or MDX file in `app/routes/posts`. The project supports frontmatter, so you can add the post metadata formatted as YAML at the top of the file. Check the posts in this repository if you need an example.

Finally, include the new post in the `POSTS` constant in the `app/utils/posts.server.ts` file. The post should be available now in your blog.
