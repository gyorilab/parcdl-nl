YAML format for model definition
--------------------------------
- name: name of the model
- description: description of the model
- units:
    - concentration: the concentration units of molecular species
    - time: the time unit associated with the model
- modules: a list of modules defining the model
    - module name
        - sentence
            - policy: the name of the assembly policy for the statement from
                the sentence
            - parameters: list of parameters
                - parameter identifier
                    - name: the name of the parameter
                    - value: the value of the parameter
