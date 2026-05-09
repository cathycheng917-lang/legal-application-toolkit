# Web-Verified Book Note Skill

## Purpose

This skill helps the user organize books into accurate, structured reading notes. It is suitable for books in law, humanities, social sciences, history, philosophy, literature, politics, and related fields.

The skill must not rely only on memory. Before generating the final reading note, it must search the web to verify key factual information, including bibliographic details, author background, publication history, major themes, and public or scholarly reception.

## Core Requirement: Web Verification First

Before producing the final output, always conduct web research when possible.

The web search should verify:

- Full book title
- Original title, if translated
- Author name
- Author background
- First publication date
- Publisher
- Edition or translation information, if relevant
- Book genre or academic field
- Main subject matter
- General reception, influence, controversy, praise, or criticism

If the user provides a Chinese translated title, try to identify the original title and original publication information.

If different sources give different information, explain the uncertainty instead of choosing one silently.

## Source Priority

Use sources in the following order:

1. Publisher website
2. Author's official website or institutional profile
3. Library catalogues, such as WorldCat, Library of Congress, university libraries, or national libraries
4. Academic databases or university pages
5. Reputable book reviews, newspapers, journals, or magazines
6. Encyclopedic sources, only as supplementary references
7. Retail websites, only for basic bibliographic information when better sources are unavailable

Avoid relying mainly on random blogs, marketing pages, or unsourced summaries.

## Anti-Hallucination Rules

- Do not invent publication dates, publishers, editions, quotations, page numbers, chapter titles, awards, or controversies.
- Do not pretend to have read the entire book if only public information is available.
- Do not fabricate direct quotations.
- If exact information cannot be verified, write "暂未确认".
- If the book has multiple editions or translations, state which edition the note is based on.
- Clearly distinguish between:
  - Verified factual information
  - Publicly available summaries
  - The model's own synthesis
  - Critical interpretation
- If the user provides their own notes or excerpts, prioritize those materials when summarizing the book's content.

## Default Output Language

Use the same language as the user's request unless the user specifies otherwise.

If the user writes in Chinese, output in polished, natural Chinese.

## Default Output Structure

# 《书名》读书整理

## 一、基本信息

- **书名：**
- **原书名：**
- **作者：**
- **首次出版时间：**
- **出版社：**
- **中译本信息：**
- **类型 / 主题领域：**
- **关键词：**
- **信息来源说明：**

If any information cannot be verified, mark it as "暂未确认".

## 二、作者简介

Introduce the author based on verified sources.

Include:

- Educational or professional background
- Main research or writing field
- Representative works
- Intellectual influence
- Relationship between the author's background and this book

Avoid unnecessary biographical details.

## 三、写作背景与问题意识

Explain:

- The historical, intellectual, social, political, or academic context of the book
- The problem the author is responding to
- Why the book matters in its field

If the background is inferred rather than directly verified, clearly mark it as an interpretation.

## 四、主要内容概述

Summarize the book's main content.

If a reliable table of contents is available, organize this section according to the book's structure.

If no reliable table of contents is available, organize by themes.

Avoid overclaiming. If the summary is based mainly on public reviews or publisher descriptions, state this clearly.

## 五、核心观点与论证逻辑

Extract 3-6 core arguments.

For each argument, use this structure:

### 观点一：

- **核心内容：**
- **论证方式：**
- **意义：**
- **依据说明：**

The "依据说明" should state whether the point comes from the user's notes, publisher description, reviews, academic discussion, or general synthesis.

## 六、值得赞赏之处

Analyze the strengths of the book.

Possible angles:

- Originality
- Structure
- Depth of argument
- Use of historical or empirical materials
- Theoretical contribution
- Practical significance
- Literary or rhetorical power
- Influence on later debates

Avoid empty praise. Every positive evaluation should be specific.

## 七、可能的局限与可批判之处

Offer a balanced critique.

Possible angles:

- Evidence may be incomplete
- Argument may be too broad or too narrow
- Certain perspectives may be underrepresented
- The framework may be limited by its historical context
- Some conclusions may be controversial or outdated
- The book may overlook alternative explanations

Do not criticize mechanically. Criticism should be fair and reasoned.

## 八、与我的研究 / 写作 / 思考的关联

Connect the book to the user's interests where appropriate, especially:

- 法学
- 国际法
- 人权法
- 国际经济法
- 政治理论
- 社会科学
- 学术写作
- 个人成长与经验反思

If the user provides a specific purpose for reading, prioritize that purpose.

## Citation Requirement

When web sources are used, cite sources clearly in the final response.

Citations should support:

- Bibliographic information
- Author biography
- Publication history
- Major claims about the book's reception or influence
- Specific praise or criticism from reviewers or scholars

Do not cite irrelevant sources.

## Output Quality Requirements

- Keep the structure clear and readable.
- Avoid vague praise such as "内容丰富" or "意义重大" unless the reason is explained.
- Use careful language when information is uncertain.
- Do not overstate the book's argument beyond what the available sources support.
- When the user's own notes conflict with public summaries, preserve the user's notes and explain the difference carefully.
