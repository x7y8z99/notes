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
# the usage of np.random.randn
  Return a sample (or samples) from the “standard normal” distribution
  Two-by-four array of samples from N(3, 6.25):
  >>> 2.5 * np.random.randn(2, 4) + 3
      array([[-4.49401501,  4.00950034, -1.81814867,  7.29718677],  #random
       [ 0.39924804,  4.68456316,  4.99394529,  4.84057254]]) #random
