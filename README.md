# Zoocha Accordion Installation Guide

To install the Zoocha Accordion, follow the steps below:

1. Open your terminal.
2. Navigate to your project directory.
3. Add the below in the Drupal Root's composer.json installer-paths
    ```sh
    "web/recipes/custom/{$name}": ["type:drupal-custom-recipe"]
    ```
4. Run the following command to execute the Zoocha Accordion installation:

    ```sh
    ddev drush recipe recipes/custom/zr-cb-accordion
    ```

This command will execute the Zoocha Accordion installation.
