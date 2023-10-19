# Data_Analysis_Lab_A
Labs College 


{
  "cells": [
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "DkS1pproE04f"
      },
      "source": [
        "Week 2Lab1 Suggested Solutions"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "1PfhiNzTE04g"
      },
      "source": [
        "# NumPy Exercises - Solutions\n",
        "\n",
        "Now that we've learned about NumPy let's test your knowledge. We'll start off with a few simple tasks and then you'll be asked some more complicated questions."
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "Wzqa0pmWE04h"
      },
      "source": [
        "#### Import NumPy as np"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "collapsed": true,
        "id": "N2VFzd4RE04h"
      },
      "outputs": [],
      "source": [
        "import numpy as np"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "yifO8m-2E04h"
      },
      "source": [
        "#### Create an array of 10 zeros"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "SNoLmMGWE04h",
        "outputId": "40b7656d-caa6-4ab2-cc23-a8a47d89717e"
      },
      "outputs": [
        {
          "data": {
            "text/plain": [
              "array([ 0.,  0.,  0.,  0.,  0.,  0.,  0.,  0.,  0.,  0.])"
            ]
          },
          "execution_count": 2,
          "metadata": {},
          "output_type": "execute_result"
        }
      ],
      "source": [
        "np.zeros(10)"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "s6lSYBSPE04i"
      },
      "source": [
        "#### Create an array of 10 ones"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "Ocb5tlolE04i",
        "outputId": "851addba-1438-4d79-c80a-d7c5dfa9f5cb"
      },
      "outputs": [
        {
          "data": {
            "text/plain": [
              "array([ 1.,  1.,  1.,  1.,  1.,  1.,  1.,  1.,  1.,  1.])"
            ]
          },
          "execution_count": 3,
          "metadata": {},
          "output_type": "execute_result"
        }
      ],
      "source": [
        "np.ones(10)"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "qrTJ_382E04i"
      },
      "source": [
        "#### Create an array of 10 fives"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "UEENBhztE04i",
        "outputId": "791e012c-908d-4005-ba0b-4139bc7d9dd1"
      },
      "outputs": [
        {
          "data": {
            "text/plain": [
              "array([ 5.,  5.,  5.,  5.,  5.,  5.,  5.,  5.,  5.,  5.])"
            ]
          },
          "execution_count": 4,
          "metadata": {},
          "output_type": "execute_result"
        }
      ],
      "source": [
        "np.ones(10) * 5"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "jrOgu2O-E04j"
      },
      "source": [
        "#### Create an array of the integers from 10 to 50"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "oAMMBHIZE04j",
        "outputId": "63b946f2-1344-465e-fd61-f7953d54dac9"
      },
      "outputs": [
        {
          "data": {
            "text/plain": [
              "array([10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, 26,\n",
              "       27, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43,\n",
              "       44, 45, 46, 47, 48, 49, 50])"
            ]
          },
          "execution_count": 5,
          "metadata": {},
          "output_type": "execute_result"
        }
      ],
      "source": [
        "np.arange(10,51)"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "IrWiQMTSE04j"
      },
      "source": [
        "#### Create an array of all the even integers from 10 to 50"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "DfChTRMbE04j",
        "outputId": "66cbbf28-5dd0-426f-ee57-b44c6858682b"
      },
      "outputs": [
        {
          "data": {
            "text/plain": [
              "array([10, 12, 14, 16, 18, 20, 22, 24, 26, 28, 30, 32, 34, 36, 38, 40, 42,\n",
              "       44, 46, 48, 50])"
            ]
          },
          "execution_count": 6,
          "metadata": {},
          "output_type": "execute_result"
        }
      ],
      "source": [
        "np.arange(10,51,2)"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "OX0vgWyrE04j"
      },
      "source": [
        "#### Create a 3x3 matrix with values ranging from 0 to 8"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "7UyX7GUBE04j",
        "outputId": "040826d3-4455-4a71-e3f5-d0db7ce668bb"
      },
      "outputs": [
        {
          "data": {
            "text/plain": [
              "array([[0, 1, 2],\n",
              "       [3, 4, 5],\n",
              "       [6, 7, 8]])"
            ]
          },
          "execution_count": 7,
          "metadata": {},
          "output_type": "execute_result"
        }
      ],
      "source": [
        "np.arange(9).reshape(3,3)"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "cQaoBWZrE04j"
      },
      "source": [
        "#### Create a 3x3 identity matrix"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "E1DT30BCE04j",
        "outputId": "63f4b112-e479-4b31-ffd4-bb5eee2faf82"
      },
      "outputs": [
        {
          "data": {
            "text/plain": [
              "array([[ 1.,  0.,  0.],\n",
              "       [ 0.,  1.,  0.],\n",
              "       [ 0.,  0.,  1.]])"
            ]
          },
          "execution_count": 8,
          "metadata": {},
          "output_type": "execute_result"
        }
      ],
      "source": [
        "np.eye(3)"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "Plsl_mJJE04j"
      },
      "source": [
        "#### Use NumPy to generate a random number between 0 and 1"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "MKxXEkaKE04k",
        "outputId": "bce65210-b337-45fd-9700-9af13ed62f51"
      },
      "outputs": [
        {
          "data": {
            "text/plain": [
              "array([ 0.42829726])"
            ]
          },
          "execution_count": 15,
          "metadata": {},
          "output_type": "execute_result"
        }
      ],
      "source": [
        "np.random.rand(1)"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "YbDv1Rp1E04k"
      },
      "source": [
        "#### Use NumPy to generate an array of 25 random numbers sampled from a standard normal distribution"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "u73LZFrHE04k",
        "outputId": "d9ad2cc8-9029-473a-c09a-62254667875f"
      },
      "outputs": [
        {
          "data": {
            "text/plain": [
              "array([ 1.32031013,  1.6798602 , -0.42985892, -1.53116655,  0.85753232,\n",
              "        0.87339938,  0.35668636, -1.47491157,  0.15349697,  0.99530727,\n",
              "       -0.94865451, -1.69174783,  1.57525349, -0.70615234,  0.10991879,\n",
              "       -0.49478947,  1.08279872,  0.76488333, -2.3039931 ,  0.35401124,\n",
              "       -0.45454399, -0.64754649, -0.29391671,  0.02339861,  0.38272124])"
            ]
          },
          "execution_count": 33,
          "metadata": {},
          "output_type": "execute_result"
        }
      ],
      "source": [
        "np.random.randn(25)"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "CKr_RuQGE04k"
      },
      "source": [
        "#### Create the following matrix:"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "JbQlKx1oE04k",
        "outputId": "597543d0-7bd0-433a-f1c2-16d7c0335d4d"
      },
      "outputs": [
        {
          "data": {
            "text/plain": [
              "array([[ 0.01,  0.02,  0.03,  0.04,  0.05,  0.06,  0.07,  0.08,  0.09,  0.1 ],\n",
              "       [ 0.11,  0.12,  0.13,  0.14,  0.15,  0.16,  0.17,  0.18,  0.19,  0.2 ],\n",
              "       [ 0.21,  0.22,  0.23,  0.24,  0.25,  0.26,  0.27,  0.28,  0.29,  0.3 ],\n",
              "       [ 0.31,  0.32,  0.33,  0.34,  0.35,  0.36,  0.37,  0.38,  0.39,  0.4 ],\n",
              "       [ 0.41,  0.42,  0.43,  0.44,  0.45,  0.46,  0.47,  0.48,  0.49,  0.5 ],\n",
              "       [ 0.51,  0.52,  0.53,  0.54,  0.55,  0.56,  0.57,  0.58,  0.59,  0.6 ],\n",
              "       [ 0.61,  0.62,  0.63,  0.64,  0.65,  0.66,  0.67,  0.68,  0.69,  0.7 ],\n",
              "       [ 0.71,  0.72,  0.73,  0.74,  0.75,  0.76,  0.77,  0.78,  0.79,  0.8 ],\n",
              "       [ 0.81,  0.82,  0.83,  0.84,  0.85,  0.86,  0.87,  0.88,  0.89,  0.9 ],\n",
              "       [ 0.91,  0.92,  0.93,  0.94,  0.95,  0.96,  0.97,  0.98,  0.99,  1.  ]])"
            ]
          },
          "execution_count": 35,
          "metadata": {},
          "output_type": "execute_result"
        }
      ],
      "source": [
        "np.arange(1,101).reshape(10,10) / 100"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "lhfZu_X5E04k"
      },
      "source": [
        "#### Create an array of 20 linearly spaced points between 0 and 1:"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "toJRGbHNE04k",
        "outputId": "22c2ece0-3b6d-45db-9025-b63ecf2c63e6"
      },
      "outputs": [
        {
          "data": {
            "text/plain": [
              "array([ 0.        ,  0.05263158,  0.10526316,  0.15789474,  0.21052632,\n",
              "        0.26315789,  0.31578947,  0.36842105,  0.42105263,  0.47368421,\n",
              "        0.52631579,  0.57894737,  0.63157895,  0.68421053,  0.73684211,\n",
              "        0.78947368,  0.84210526,  0.89473684,  0.94736842,  1.        ])"
            ]
          },
          "execution_count": 36,
          "metadata": {},
          "output_type": "execute_result"
        }
      ],
      "source": [
        "np.linspace(0,1,20)"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "3YrIP6O3E04k"
      },
      "source": [
        "## Numpy Indexing and Selection\n",
        "\n",
        "Now you will be given a few matrices, and be asked to replicate the resulting matrix outputs:"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "BzWXEMoME04k",
        "outputId": "a033cc69-2117-4d13-da30-3cc8fc977db8"
      },
      "outputs": [
        {
          "data": {
            "text/plain": [
              "array([[ 1,  2,  3,  4,  5],\n",
              "       [ 6,  7,  8,  9, 10],\n",
              "       [11, 12, 13, 14, 15],\n",
              "       [16, 17, 18, 19, 20],\n",
              "       [21, 22, 23, 24, 25]])"
            ]
          },
          "execution_count": 38,
          "metadata": {},
          "output_type": "execute_result"
        }
      ],
      "source": [
        "mat = np.arange(1,26).reshape(5,5)\n",
        "mat"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "collapsed": true,
        "id": "40QBxOVkE04k"
      },
      "outputs": [],
      "source": [
        "# WRITE CODE HERE THAT REPRODUCES THE OUTPUT OF THE CELL BELOW\n",
        "# BE CAREFUL NOT TO RUN THE CELL BELOW, OTHERWISE YOU WON'T\n",
        "# BE ABLE TO SEE THE OUTPUT ANY MORE"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "uJ6VHatHE04k",
        "outputId": "6f54c7a4-91cd-4f23-da6d-e84fc86357f8"
      },
      "outputs": [
        {
          "data": {
            "text/plain": [
              "array([[12, 13, 14, 15],\n",
              "       [17, 18, 19, 20],\n",
              "       [22, 23, 24, 25]])"
            ]
          },
          "execution_count": 40,
          "metadata": {},
          "output_type": "execute_result"
        }
      ],
      "source": [
        "mat[2:,1:]"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "collapsed": true,
        "id": "apVWLA71E04k"
      },
      "outputs": [],
      "source": [
        "# WRITE CODE HERE THAT REPRODUCES THE OUTPUT OF THE CELL BELOW\n",
        "# BE CAREFUL NOT TO RUN THE CELL BELOW, OTHERWISE YOU WON'T\n",
        "# BE ABLE TO SEE THE OUTPUT ANY MORE"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "4un9DECjE04l",
        "outputId": "5d2a426c-acc5-4875-e7d1-eac56b6ee159"
      },
      "outputs": [
        {
          "data": {
            "text/plain": [
              "20"
            ]
          },
          "execution_count": 41,
          "metadata": {},
          "output_type": "execute_result"
        }
      ],
      "source": [
        "mat[3,4]"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "collapsed": true,
        "id": "HWjjLgIcE04l"
      },
      "outputs": [],
      "source": [
        "# WRITE CODE HERE THAT REPRODUCES THE OUTPUT OF THE CELL BELOW\n",
        "# BE CAREFUL NOT TO RUN THE CELL BELOW, OTHERWISE YOU WON'T\n",
        "# BE ABLE TO SEE THE OUTPUT ANY MORE"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "nl3IEvzhE04l",
        "outputId": "dbf80440-2899-447c-e895-562015daf310"
      },
      "outputs": [
        {
          "data": {
            "text/plain": [
              "array([[ 2],\n",
              "       [ 7],\n",
              "       [12]])"
            ]
          },
          "execution_count": 42,
          "metadata": {},
          "output_type": "execute_result"
        }
      ],
      "source": [
        "mat[:3,1:2]"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "collapsed": true,
        "id": "5DkuN1aGE04l"
      },
      "outputs": [],
      "source": [
        "# WRITE CODE HERE THAT REPRODUCES THE OUTPUT OF THE CELL BELOW\n",
        "# BE CAREFUL NOT TO RUN THE CELL BELOW, OTHERWISE YOU WON'T\n",
        "# BE ABLE TO SEE THE OUTPUT ANY MORE"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "V-OjvKxYE04l",
        "outputId": "30caa4aa-4c27-4728-ebe9-e1d1ee08482e"
      },
      "outputs": [
        {
          "data": {
            "text/plain": [
              "array([21, 22, 23, 24, 25])"
            ]
          },
          "execution_count": 46,
          "metadata": {},
          "output_type": "execute_result"
        }
      ],
      "source": [
        "mat[4,:]"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "collapsed": true,
        "id": "RC7TjpRiE04l"
      },
      "outputs": [],
      "source": [
        "# WRITE CODE HERE THAT REPRODUCES THE OUTPUT OF THE CELL BELOW\n",
        "# BE CAREFUL NOT TO RUN THE CELL BELOW, OTHERWISE YOU WON'T\n",
        "# BE ABLE TO SEE THE OUTPUT ANY MORE"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "IJJ0ratHE04l",
        "outputId": "5a2f5c13-0857-4a7b-ed0c-9c55d3d8237a"
      },
      "outputs": [
        {
          "data": {
            "text/plain": [
              "array([[16, 17, 18, 19, 20],\n",
              "       [21, 22, 23, 24, 25]])"
            ]
          },
          "execution_count": 49,
          "metadata": {},
          "output_type": "execute_result"
        }
      ],
      "source": [
        "mat[3:5,:]"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "FCD__VFIE04l"
      },
      "source": [
        "### Now do the following"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "KfYqLevWE04p"
      },
      "source": [
        "#### Get the sum of all the values in mat"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "icE78gkME04p",
        "outputId": "1465daf3-aa34-45e2-f366-ead068d36dfa"
      },
      "outputs": [
        {
          "data": {
            "text/plain": [
              "325"
            ]
          },
          "execution_count": 50,
          "metadata": {},
          "output_type": "execute_result"
        }
      ],
      "source": [
        "mat.sum()"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "TJhlBLqwE04p"
      },
      "source": [
        "#### Get the standard deviation of the values in mat"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "3OkbZIbiE04p",
        "outputId": "dac7c120-f23f-45e8-e29e-5a77dab9c96f"
      },
      "outputs": [
        {
          "data": {
            "text/plain": [
              "7.2111025509279782"
            ]
          },
          "execution_count": 51,
          "metadata": {},
          "output_type": "execute_result"
        }
      ],
      "source": [
        "mat.std()"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "PoWin6vmE04p"
      },
      "source": [
        "#### Get the sum of all the columns in mat"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "ZcAStKTmE04p",
        "outputId": "5c36fe75-0c9d-406c-f7bd-037e38970cf6"
      },
      "outputs": [
        {
          "data": {
            "text/plain": [
              "array([55, 60, 65, 70, 75])"
            ]
          },
          "execution_count": 53,
          "metadata": {},
          "output_type": "execute_result"
        }
      ],
      "source": [
        "mat.sum(axis=0)"
      ]
    }
  ],
  "metadata": {
    "kernelspec": {
      "display_name": "Python 3",
      "language": "python",
      "name": "python3"
    },
    "language_info": {
      "codemirror_mode": {
        "name": "ipython",
        "version": 3
      },
      "file_extension": ".py",
      "mimetype": "text/x-python",
      "name": "python",
      "nbconvert_exporter": "python",
      "pygments_lexer": "ipython3",
      "version": "3.5.1"
    },
    "colab": {
      "provenance": []
    }
  },
  "nbformat": 4,
  "nbformat_minor": 0
}
