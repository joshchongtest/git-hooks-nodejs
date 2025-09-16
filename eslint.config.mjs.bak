import js from "@eslint/js";
import globals from "globals";
import { defineConfig } from "eslint/config";
import airbnbBase from "eslint-config-airbnb-base";

export default defineConfig([
  {
    files: ["**/*.{js,mjs,cjs}"],
    plugins: { js },
    extends: [airbnbBase, "js/recommended"],
    languageOptions: { globals: globals.browser },
  },
  { files: ["**/*.js"], languageOptions: { sourceType: "commonjs" } },
]);
