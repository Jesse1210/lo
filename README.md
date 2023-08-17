# lo
def gen_conditions():
    # We need to distribute complexity (= distance)
    # Each condition is a position and an object
    max_distance = 2
    max_time = 0
    def distribute(n, bins, n_max):
    """
    Distributes the integer `n` into `bins` number of terms that sum to n.
  1452
