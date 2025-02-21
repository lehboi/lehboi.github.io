# Responsive Sample Page

This is a sample markdown page designed to be responsive to different screen sizes. It uses HTML and CSS within the markdown to achieve responsiveness.

## Header

This header will adjust based on the screen size.

## Table of Contents

1. [Introduction](#introduction)
2. [Responsive Images](#responsive-images)
3. [Responsive Tables](#responsive-tables)
4. [CSS Media Queries](#css-media-queries)

## Introduction

In this sample, we demonstrate how to make a markdown page responsive using CSS and HTML.

## Responsive Images

To make images responsive, you can use CSS styles. Here's an example:

```html
<img src="https://via.placeholder.com/800x400" alt="Sample Image" style="width:100%; height:auto;">
```

## Responsive Tables

Tables can also be made responsive by wrapping them in a div with `overflow-x: auto;`. Here's an example:

```html
<div style="overflow-x: auto;">
  <table>
    <thead>
      <tr>
        <th>Header 1</th>
        <th>Header 2</th>
        <th>Header 3</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Data 1</td>
        <td>Data 2</td>
        <td>Data 3</td>
      </tr>
      <tr>
        <td>Data 4</td>
        <td>Data 5</td>
        <td>Data 6</td>
      </tr>
    </tbody>
  </table>
</div>
```

## CSS Media Queries

To adjust styles based on screen size, use CSS media queries. Here's a simple example:

```html
<style>
  body {
    font-family: Arial, sans-serif;
  }

  @media (max-width: 600px) {
    body {
      background-color: lightblue;
    }
  }

  @media (min-width: 601px) {
    body {
      background-color: white;
    }
  }
</style>
```

In this example, the background color changes based on the screen width.

## Conclusion

By using HTML and CSS within markdown, you can create responsive designs that adjust to different screen sizes, improving the user experience on various devices.

### Footer

This is the footer of the responsive sample page.
```` ▋
