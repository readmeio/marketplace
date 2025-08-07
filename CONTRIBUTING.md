# Contribution Guidelines
We appreciate your interest in contributing to ReadMe's MDX Component Marketplace! 🎉 To maintain quality and consistency, please follow the guidelines below.

## 📋 Prerequisites
- Familiarity with React, MDX, and Tailwind CSS.
- Node.js v18+ and npm (or yarn/pnpm).
- ESLint + Prettier configured locally (the repo includes configs).

## 🛠 Development Setup
To create your component locally:
1. Clone the repository:
    ```
    git clone https://github.com/readmeio/marketplace.git
    ```
2. Install dependencies:
    ```
    npm install
    ```
3. Copy and paste the [ExampleComponent](https://github.com/readmeio/marketplace/tree/main/components/ExampleComponent) folder to use as a starter template.

## 🧩 Component Requirements
When contributing a new MDX component:
- **File Location**
    - Place your component under a new `components/YourComponentName/` folder.
    - Write your component in a `YourComponentName.mdx` file.
    - Include a `README.md` file for documentation.

- **Naming**
    - Use PascalCase for component names (e.g., CardGrid.mdx).
    - Avoid generic names like Test or Component.

- **Structure**
    ```
    ---
    title: "ExampleComponent"
    description: "The template component for creating custom components."
    author: "ReadMe"
    version: "2.0.0"
    license: "MIT"
    ---
    
    export const ExampleComponent = ({ header }) => {
      return (
        <div className="flex justify-center">
          <p className="text-lg font-bold">{header}</p>
        </div>
      );
    };
    
    <ExampleComponent header="Getting Started with Custom Components" />
    ```
    
- **Styling**
  - Try to use Tailwind classes only. External CSS or `style` tags if necessary.
  - Use semantic HTML (e.g., button for buttons, nav for navigation).

- **Accessibility**
  - Add alt text for all images.
  - Ensure keyboard navigability.
  - Use appropriate ARIA roles when needed.
 
- **Frontmatter**
  - Every component’s MDX file should start with a frontmatter that includes a title, descrption, author, version, and license.

- **Licensing**
  - Declare your license in the frontmatter (license: MIT, Apache-2.0, etc.).
  - Only contribute components you have the right to share.

## 📦 Testing Your Component
- Each component must include a usage example in its MDX file.
- You can verify your component renders correctly in your ReadMe project's [Custom Components Builder](https://docs.readme.com/main/docs/building-custom-mdx-components#getting-started-with-custom-components).
- Ensure your component name does not conflict with other marketplace components.

## 🔄 Submitting Your Contribution
1. Create a new branch:
    ```
    git checkout -b feature/my-component
    ```

2. Commit your changes:
    ```
    git commit -m "Add <ComponentName> component"
    ```

3. Push your branch and open a Pull Request.

4. In your PR description, include:
    - Component name
    - Overview description
    - Screenshot or video of the component
    - Usage example
    - Table of props including name, type, and description

## 🔍 Review Process
Maintainers will review your PR for:
- Code quality and style
- Accessibility
- Correct Tailwind usage
- Proper frontmatter metadata

You may be requested to make changes before approval.

## 🙌 Thanks!
Your contributions help grow this Marketplace. Together, we’re building a high-quality library of reusable, accessible, and beautifully styled MDX components 💙
