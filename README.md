# Chat with your text or PDF files... and maybe even get some PDF jokes along the way!

**Doc_QA_LangChain** is a web app that's here to add some humor to your document-related inquiries. It's a front-end-only marvel that lets you upload PDFs or various text-based files (txt, markdown, JSON, HTML, you name it) and interrogate them with the help of our trusty GPT companion. We've armed it with Vue3 for a dash of interactivity, dressed it up in the latest Tailwind CSS attire, and equipped it with the formidable LangChain for all its document wizardry, including creating vector stores and questioning your beloved LLM (Long-Lost Manuscript).

## What It Does

1. PDFs? Text files? Bring 'em on!
2. We chop those documents into bite-sized, 1000-token chunks (GPT's way of portion control).
3. Each chunk gets its own identity with GPT's embeddings.
4. We stash these embeddings into our fancy, ephemeral document store (it's like the VIP section for your data).
5. When you ask a question, we create a question's embedding to find the perfect document chunks to interrogate.
6. GPT delivers the verdict, and we display it with pride in the text area.

## Installation

To have some document-related fun:

1. Clone this quirky project.
2. Run `npm install` and let the magic brew.
3. Finally, execute `npm run dev` to get the party started.

## Usage
Once the project's all fired up, fire up your web browser, and head to the URL Vite generously provides. Now, you can upload those PDFs and text-based files and let the questioning begin. Who knew interrogating your documents could be this entertaining?

## Technologies Used

- Vue3: Making interactivity look easy.
- Tailwind CSS: Our stylistic superhero, making sure we look good while we work.
- LangChain: The unsung hero behind the scenes, helping us unravel the mysteries of documents and LLMs.

## License
This project isn't just about questions and answers; it's also about fun. So, it's licensed under the MIT License, where "MIT" stands for "Make It Tickle" (not really, but we wish it did). See the LICENSE file for all the non-serious details.
