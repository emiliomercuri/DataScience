# materiais de aula


## Aula 3 - dataset de emissão de CO2 por carros

"https://www.dropbox.com/s/yevoao0jiu3d5la/data.csv?dl=1"

## Código para substituir valores da série do pandas de direção do vento

wd_graus = wd_graus.replace({' N'  :  0})
wd_graus = wd_graus.replace({' NE':  45})
wd_graus = wd_graus.replace({' E'  : 90})
wd_graus = wd_graus.replace({' SE': 135})
wd_graus = wd_graus.replace({' S' : 180})
wd_graus = wd_graus.replace({' SW': 225})
wd_graus = wd_graus.replace({' W' : 270})
wd_graus = wd_graus.replace({' NW': 315})

wd_graus = wd_graus.replace({' ENE'  :  67.5})
wd_graus = wd_graus.replace({' NNE'  :  22.5})
wd_graus = wd_graus.replace({' NNW'  :  337.5})
wd_graus = wd_graus.replace({' WSW'  :  247.5})
wd_graus = wd_graus.replace({' ESE'  :  112.5})
wd_graus = wd_graus.replace({' WNW'  :  292.5})
wd_graus = wd_graus.replace({' SSW'  :  202.5})
wd_graus = wd_graus.replace({' SSE'  :  157.5})

wd_graus = wd_graus.replace({' ENE'  :  67.5})
wd_graus = wd_graus.replace({' NNE'  :  22.5})
wd_graus = wd_graus.replace({' NNW'  :  337.5})
wd_graus = wd_graus.replace({' WSW'  :  247.5})
wd_graus = wd_graus.replace({' ESE'  :  112.5})
wd_graus = wd_graus.replace({' WNW'  :  292.5})
wd_graus = wd_graus.replace({' SSW'  :  202.5})
wd_graus = wd_graus.replace({' SSE'  :  157.5})
