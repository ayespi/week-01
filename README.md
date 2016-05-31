# Week 01

## Instructions

1. Fork this repo
2. Clone your fork
3. Fill in your answers by writing in the appropriate area, or placing an 'x' in
the square brackets (for multiple-choice questions).
4. Add/Commit/Push your changes to Github.
5. Open a pull request.

## HTML

### Question #1

What does it mean for an HTML tag to be "semantic"? Give an example of a short snippet of HTML written using semantic tags and non-semantic tags.

```text
When an HTML tag is semantic, it means that the name of the tag is related to the function of the tag.
Examples:

Semantic
<header>This is the Page Header</header>
<footer>This is the Page Footer</footer>

Non-semantic
<b>This is Bold text</b>
<i>This is Italicized text</i>

```

### Question #2

What is the purpose of the `alt` attribute? e.g:

```html
<img src='https://jesse.sh/img/me.jpg' alt='Jesse Shawl'/>
```

```text
The purpose of the ALT tag is to provide assistance to visually impaired users.
In the event that the sourced image does not load into the browser, the value
associated with the ALT attribute will appear in the browser .
```

### Question #3

What is the purpose of the `<head></head>` tag in HTML?

```text
The purpose of the HEAD tag is to provide a container for HEAD elements, which
are various pieces of information related to the particular webpage. The HEAD
section includes content that does not appear in the browser when the page
is loaded.
```

## CSS

### Question #4

In the spaces below, write the CSS property that best matches the given description.

The choices are `border`, `outline`, `padding`, and `margin`. You will leave two spaces blank.

Your Answer:

```text
margin:   Defines the distance between an element's border and adjacent elements' borders.
border:   Inserts a "wall" around an element.
padding:  Defines the distance between an element's content and its border.
___:      Defines the width of an element.
outline:  Overlays a "wall" on top of an element.
___:      Defines the distance between the center of an element and the center of the adjacent element.
```

### Question #5

What does the following selector do?  `ul.dropdown > li`?

Select 1:
```
[X] Selects all li's which are directly inside a ul of class dropdown (children)
[] Selects all li's which are anywhere inside a ul of class dropdown (any descendant)
[] Selects all ul's of class dropdown, as well as the children elements that are li's
[] Selects all ul's of class dropdown, only if their children are exclusively li's
```

### Question #6

Identify the three places CSS can go, and rank them in terms of specificity:

```text
1.Inline    |  *** Most specific *** Applies only to a specific tag
2.Internal  |  Applies ONLY to a specific document
3.External  |  *** Least specific *** Cap apply to ANY document
```

## Git

### Question #7

Which of the following represents a correct workflow for submitting a PR on a non-master branch?
(ignore the lack of commit messages)

Select 1:
```
[X] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <ga_dc_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git push; create pull request
[] git clone <ga_dc_url>; git branch <charlie_solution>; git add <files>; git commit; git push; create pull request
[] fork on github; git clone <fork_url>; git checkout -b <charlie_solution>; git add <files>; git commit; git pull; create pull request
```

### Question 8

What is the difference between a fork and a clone?

```text
A Fork is copying the contents of one Remote repository to another Remote repository.

A Clone is copying the contents of a remote repository to a Local repository.
```

### Question 9

How is `git pull` related to `git fetch`?

```text
git pull | Allows you to fetch the contents of a repository and merge with
            another repository (or local branch).

git fetch | Allows you to fetch the contents of a repository to update another
            repository, with no merge.
```
