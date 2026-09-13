+++
title = 'Donate Books'
date = 2026-08-14T07:07:07+01:00
draft = false
showAuthor = false
showDate = true
showWordCount = false
showReadingTime = false
showRelatedContent = false
showPagination = false
+++

## Overview 

We accept a wide range of donated books. If you have a small bag of books, pop into the library today and hand them over to one of our volunteers at our reception desk! Otherwise, if you have more than a few bags, please contact us beforehand, as we need to check if there is sufficient space to store them.  

> [!IMPORTANT]
> We are unable to accept accounting books and large encylopedias.

## What we do with donated books

Once you donate a book, one of three things happens:

* We may add the book to the library catalogue
* We may sell the book on Ziffit or eBay to raise funds for the library
* We may pass the book onto [Freecycle](https://www.freecycle.org)

{{< accordion mode="open" separated=true >}}

  {{< accordionItem title="Our process" icon="code" open=false md=false >}}

        {{< mermaid >}}

            flowchart TD

                A[Books donated to the Library] --> B{Add to Library collection?}

                B -->|Yes| C[Catalogue and put on shelf]

                B -->|No| D{Suitable for eBay?}

                D -->|Yes| E[Sell on eBay]

                D -->|No| F[Scan with Ziffit]

                F --> G{High Value?}

                G -->|Yes| E

                G -->|No| H[Donate to Freecycle]

                H --> I[Store in storage unit]

                I --> J[Collected by Freecycle]
        {{< /mermaid >}}
  {{< /accordionItem >}}

{{< /accordion >}}
