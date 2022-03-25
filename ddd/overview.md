# 🙂&nbsp;Overview

---

### What does DDD stand for?
- Domain-Driven Design

### What is DDD?
- A method of software development

### What is Software Development?
- Solving a specific problem that happens in a specific area

### What is Domain?
- A target area that is going to be approached to solve a problem by software development

### What kind of approach does DDD take?
- Improve the value of the software by modeling optimization

> Many projects do modeling work without getting much real benefit in the end. The patterns of DDD distill successful practices from projects where dramatic benefits have come from modeling.

(from [DDD Reference](https://www.domainlanguage.com/product/domain-driven-design-reference/))

### What is Model in DDD?
- A concept of abstractions of a particular aspect of a thing in order to deliver solutions related to a domain

e.g.
```ts
type Book = {
  title: string;
  author: string;
  price: number;
}
```
In real world, there are way more info to determine a book as a particular book. But in a code base, a book is defined by that three properties, `title`, `author`, and `price`, for example. This is an analogy of the abstraction. The developer who set the `type Book`, pick the three elements to express the concept of books in the code base world. 

## ☝️&nbsp;Summary
- A problem that is wanted to be solved happens in a particular area called domain.
- To provide a solution, developers implement software
- To build software, actual related objects are needed to be sublimated to abstractions to get been able to control in code world called as model

