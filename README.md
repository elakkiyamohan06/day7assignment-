# day7assignment-
letsupgrade 
{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "name": "Day 7 Assignment.ipynb",
      "provenance": [],
      "collapsed_sections": []
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    }
  },
  "cells": [
    {
      "cell_type": "code",
      "metadata": {
        "id": "N0t3EdcHXNhP",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 51
        },
        "outputId": "13615822-271c-484c-f430-bdbef7a844bb"
      },
      "source": [
        " odd = [2, 4, 6, 8]\n",
        "  \n",
        "odd[0] = 1            \n",
        " \n",
        "print(odd)\n",
        " \n",
        " \n",
        "odd[1:4] = [3, 5, 7]  \n",
        " \n",
        "print(odd)"
      ],
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "[1, 4, 6, 8]\n",
            "[1, 3, 5, 7]\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "pVuigr_BYREv",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 106
        },
        "outputId": "2b300978-6552-41c6-80ca-2f16f82794e9"
      },
      "source": [
        " \n",
        "my_tuple = ('p','r','o','g','r','a','m','i','z')\n",
        " \n",
        "print(my_tuple[1:4])\n",
        " \n",
        "print(my_tuple[:-7])\n",
        " \n",
        " \n",
        "print(my_tuple[7:])\n",
        " \n",
        "print(my_tuple[:])"
      ],
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "('r', 'o', 'g')\n",
            "('p', 'r')\n",
            "('i', 'z')\n",
            "('p', 'r', 'o', 'g', 'r', 'a', 'm', 'i', 'z')\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "x0ThZI9gZP68",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 71
        },
        "outputId": "efa7f3f8-c4fd-4032-a6b8-d69e324a5f31"
      },
      "source": [
        " \n",
        "my_tuple = (4, 2, 3, [6, 5])\n",
        " \n",
        " \n",
        " \n",
        "my_tuple[3][0] = 9   \n",
        "print(my_tuple)\n",
        " \n",
        " \n",
        "my_tuple = ('p', 'r', 'o', 'g', 'r', 'a', 'm', 'i', 'z')\n",
        "print(my_tuple)"
      ],
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "(4, 2, 3, [9, 5])\n",
            "('p', 'r', 'o', 'g', 'r', 'a', 'm', 'i', 'z')\n"
          ],
          "name": "stdout"
        }
      ]
    }
  ]
}
