# TemplateParametersBundle
====================

This bundle helps you to replace parameters in templates for your Symfony 4/5 application

## Installation

### Step 1: Install the bundle

    $ composer require dmytrof/template-parameters-bundle 

### Step 2: Enable the bundle

    <?php
        // config/bundles.php
        
        return [
            // ...
            Dmytrof\TemplateParametersBundle\DmytrofTemplateParametersBundle::class => ['all' => true],
        ];
        
        