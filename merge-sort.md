# [16,21,11,8,12,22] dizisinin Merge Sort yöntemine göre sıralanma adımları:

## 1. Dizi iki parçaya bölünür: O(logn)
### Sol parça: [16, 21, 11]
### Sağ parça: [8, 12, 22]

## 2. Her iki parça, yine parçalara ayrılır. 
### Sol parça: 
#### 1. [16]
#### 2. [21,11]

### Sağ parça: 
#### 1. [8]
#### 2. [12,22]

### 3. Her parça kendi arasında sıralanır.
### Sol parça: 
#### 1. [16]
#### 2. [11,21]

### Sağ parça: 
#### 1. [8]
#### 2. [12,22]


### 4. Sol ve sağ parçalar kendi arasında sıralanarak birleştirilir. 
### Sol parça: 
#### [11,16,21]

### Sağ parça: 
#### [8,12,22] 

### 5. Sol ve Sağ parçalarak sıralanarak birleştirilir.
#### [8,11,12,16,21,22]


# Big-O gösterimi:
## Her aşamada yapılan işlem >>> O(n)
## Bu işlem >>> O(logn) kere yapılır.
## Dolayısıyla Merge Sort >>> O(nlogn) olur.