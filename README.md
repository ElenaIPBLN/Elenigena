# Elenigena
curso reproducibilidad
Material para el curso de formacion CSIC
## Aim of this repository
This is my first repository to store information from my research on Parkinson.

## How to collaborate:

- One: Clone this repository.
- Two: Add your features and collaborate with us on this research project.

## How to cite this repository

	@misc{Elenigena2022,
  		author = {ElenaIPBLN},
  		title = {Elenigena},
  		year = {2022},
  		publisher = {GitHub},
  		journal = {GitHub repository},
  		howpublished = {\url{URL_OF_THIS_REPO}}
		}
## Contributors

- ElenaIPBLN
		
/funtions/plot.py
import matplotlib.pyplot as plt
fig = plt.figure()
ax = fig.add_axes([0,0,1,1])
langs = ['C', 'C++', 'Java', 'Python', 'PHP']
students = [23,17,35,29,12]
ax.bar(langs,students)
plt.show()
