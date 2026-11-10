# Flutter Week 4 – Navigation and Routing

This repository contains two Flutter examples focused on moving between screens and passing data through routes.

## Exercises

| File | Description |
|---|---|
| `4(A)` | Screen navigation using `Navigator.push`, named routes, route replacement and an unknown-route fallback |
| `4(B)` | Named routes with `onGenerateRoute`, typed route arguments, an About page, a Details page and an unknown-page fallback |
| `output_4a.jpeg`, `output_4b.jpeg` | Screenshots of the exercise outputs |

## Concepts covered

- `Navigator.push` and `Navigator.pushNamed`
- Registering routes in `MaterialApp`
- Replacing a route and returning through the navigation stack
- Handling unknown route names
- Passing data to a destination screen with route arguments
- Creating screens with `Scaffold` and Material widgets

## Run an exercise

The repository contains source examples and screenshots, not a complete Flutter project.

```bash
flutter doctor
flutter create navigation_demo
cd navigation_demo
```

Copy the contents of `4(A)` or `4(B)` into `lib/main.dart`, then run:

```bash
flutter run
```

## Learning objective

Understand how to organize a multi-screen Flutter app, choose between direct and named navigation, and transfer simple data between pages.
