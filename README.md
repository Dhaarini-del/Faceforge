FaceForge is a specialized forensic digital composite application designed for law enforcement and investigative purposes. It streamlines the creation of facial sketches by leveraging AI-driven generation and natural language processing to translate verbal witness statements into high-definition visual representations.

Key Features:
Witness Statement Processing: The system allows investigators to input verbatim interview transcripts. It then automatically extracts key physiological data—such as age, skin tone, hair style, eye shape, and distinguishing marks (e.g., scars or stubble)—to build an initial composite.
Iterative Refinement with Feature Locking: Investigators can refine sketches through incremental text feedback (e.g., "narrower nose"). The "Feature Locks" mechanism ensures that confirmed features remain unchanged during subsequent AI iterations, maintaining the integrity of the sketch.

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
