# Folder structure

This document describes the rules to follow hen it comes to organize folders on my frontend projects.

- Use kebab case for folder names
- All code will reside on a "src" folder that will contain all the business logic
- Create features based on the areas of business the app has. Some examples: "auth", "payments", "dashboard", "user-profile", etc
- Inside every area of business, there can be different features that will follow the same convention. For example, inside "payments" you can have "shopping-cart", "summary", "thanks-for-shopping", etc
- Avoid creating folders that describe what type of code lives inside. For example "components", "constants", "types", etc
