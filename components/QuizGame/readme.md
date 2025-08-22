# QuizGame

## Overview

A `<QuizGame />` can be used to render a question with multiple-choice answers, let the user select an option, and then check if the answer is correct.

## Usage

```mdx
<QuizGame
  question="What does DOM stand for?"
  options={[
    { text: 'Document Object Model', isCorrect: true },
    { text: 'Data Object Model', isCorrect: false },
    { text: 'Digital Oriented Model', isCorrect: false },
    { text: 'Document Oriented Markup', isCorrect: false },
  ]}
/>
```

## Props

| Prop       | Type   | Description                     |
| ---------- | ------ | ------------------------------- |
| `question` | string | The title displayed at the top. |
| `options`  | string | The title displayed at the top. |
