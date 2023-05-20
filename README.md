# NLP-Project
Template Filling using NLP
This project uses Natural Language Processing techniques to automatically fill in templates based on input text.

Problem Statement
Filling out forms and templates with information can be a tedious process. This project aims to automate the process of extracting relevant information from input text and filling out templates.

Data
The data for this project consists of:

    Input text documents containing information
    Templates with empty fields that need to be filled

Methods
The following NLP methods are used:

    Named Entity Recognition to identify entities like people, organizations, locations, etc. from the input text
    Relation extraction to determine relationships between entities
    Information extraction to extract relevant info and facts from the text
    Fill-in-the-blank techniques to place extracted information into the appropriate fields of the templates

Usage
To use the template filling model:
Import the TemplateFilling class
Initialize the model by passing in a list of input documents and a list of templates

Call the fill_templates() method by passing in the text and template you want to fill:

    from template_filling import TemplateFilling

# Initialize model 
    model = TemplateFilling(input_docs, templates) 

# Fill template 
    filled_template = model.fill_templates(input_text, template)  
    The filled_template will contain the template with all empty fields filled in based on the input text.
Future Work
    Improve named entity recognition for higher accuracy
    Develop better relation extraction techniques to capture more complex relations
    Expand to more types of templates and domains
