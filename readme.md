# 2 layer

def initialize_parameters(n_x, n_h, n_y):

    ...

    return parameters 

def linear_activation_forward(A_prev, W, b, activation):

    ...
    
    return A, cache

def compute_cost(AL, Y):
    
    ...
    
    return cost

def linear_activation_backward(dA, cache, activation):
    
    ...
    
    return dA_prev, dW, db

def update_parameters(parameters, grads, learning_rate):
    
    ...
    
    return parameters


# L layer

layer_dims_example:

layers_dims = [12288, 20, 7, 5, 1]


def initialize_parameters_deep(layer_dims):
    
    ...
    
    return parameters 

def L_model_forward(X, parameters):
    
    ...
    
    return AL, caches

def compute_cost(AL, Y):
    
    ...
    
    return cost

def L_model_backward(AL, Y, caches):
    
    ...
    
    return grads

def update_parameters(parameters, grads, learning_rate):
    
    ...
    
    return parameters
