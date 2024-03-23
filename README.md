This repository is based on the [example code of notion-react-x](https://github.com/NotionX/react-notion-x/tree/v6.16.2/examples/full) and utilize the [Static Exports](https://nextjs.org/docs/pages/building-your-application/deploying/static-exports) feature of Next.js to perform an comprehensive backup of a Notion page.

## Getting Started

1. Install dependencies:

    ```bash
    yarn install
    ```

2. Edit `lib/config.ts` to specify the page ID to backup.

3. Build and export the page.

    ```bash
    yarn build
    ```

4. The page backup is stored in `out/` directory.
