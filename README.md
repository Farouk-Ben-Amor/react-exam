# Intro

I implemented the features outlined in the task description and ensured that the application follows the provided Figma mockups on both desktop and mobile views. more details are in the codebase.

## Assignment

- ✅ Modern react utilities
- ✅ Responsive Layout
- ✅ Formatting & Linting
- ✅ Typechecking & Typesafety
- ✅ Git flow and static Deployment

## Choices

- I didn't create many small componenets to avoid unecessary complexity
- I used context to avoid prop drilling
- I added an interface for the Products JSON for typesafety
- I added a loading state
- I used SVG Icons for the input areas (arrows, dollar sign)
- I deployed the app to Vercel (PaaS)

### Notes

> The Dockerfile uses the latest node version (20.x) but the project depends on Node 16, that's why instead of using Docker Compose, I recreated the project from scratch using vite (instead of webpack) to use the latest React and Node version
