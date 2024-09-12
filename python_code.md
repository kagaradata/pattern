# Код №1

class Scanner:
    
    def __init__(self, input_stream):
        self._input_stream = input_stream

    def __del__(self):
        pass  

    def scan(self):
        pass

# Код №2

class Parser:
    def __init__(self):
        pass  

    def __del__(self):
        pass  

    def parse(self, scanner, program_node_builder):
        pass  

# Код №3 

class ProgramNodeBuilder:
    
    def __init__(self):
        self._node = None  

    def new_variable(self, variable_name: str) -> 'ProgramNode':
        pass  

    def new_assignment(self, variable: 'ProgramNode', expression: 'ProgramNode') -> 'ProgramNode':
        pass  

    def new_return_statement(self, value: 'ProgramNode') -> 'ProgramNode':
        pass  

    def new_condition(self, condition: 'ProgramNode', true_part: 'ProgramNode', false_part: 'ProgramNode') -> 'ProgramNode':
        pass  

    def get_root_node(self) -> 'ProgramNode':
        return self._node  

# Код №4

class ProgramNode:
    
    def __init__(self):
        pass 

    def get_source_position(self):
        return None  

    def add(self, child_node):
        pass  

    def remove(self, child_node):
        pass  

    def traverse(self, code_generator):
        pass  
