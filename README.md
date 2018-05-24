# notes
python
# the usage of '_'
  As a general purpose "throwaway" variable name to indicate that part of a function result is being deliberately ignored, 
  as in code like: label, has_label, _ = text.partition(':')
  
# the usage of np.random.rand
  Random values in a given shape.
  Create an array of the given shape and populate it with random samples from a uniform distribution over [0, 1).
  Examples
  >>> np.random.rand(3,2)
  array([[ 0.14022471,  0.96360618],  #random
       [ 0.37601032,  0.25528411],  #random
       [ 0.49313049,  0.94909878]]) #random
