# ABM6.geometry1
def get_distance(x0, y0, x1, y1):
    x = x1 - x0
    y = y1 - y0
    return (x*x + y*y) ** 0.5
