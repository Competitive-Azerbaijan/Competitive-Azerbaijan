# Codeforces - Domino Piling

# Sual

[Suala Keçid](https://codeforces.com/problemset/problem/50/A)

Sizə M x N (eni M, uzunluğu N) düzbucaqlı lövhə verilib. Bundan başqa, limitsiz sayda eni 2, uzunluğu 1 olan domino parçaları verilib. Parçaları döndərməyə icazə verilir. Aşağıdakı şərtlərə cavab verməklə lövhədə mümkün qədər çox domino parçası yerləşdirməyiniz xahiş olunur:

1. Dominoları şaquli və ya üfüqi şəkildə yerləşdirmək olar.

2. İki domino parçası üst-üstə düşmür.

3. Hər domino parçası tamamilə lövhənin içərisində olmalıdır. Lövhənin kənarlarına toxunmağa icazə verilir.

Bu şərtləri ödəməklə lövhənin içində maksimum neçə domino parçası yerləşdirmək olar?

### Giriş(Input):

Birinci sətirdə sizə M və N ədədləri veriləcək.(1 <= M <= N <= 16)

### Çıxış(Output):

Bir ədəd - Verilmiş lövhədə yerləşdirilə biləcək maksimum domino parçalarının sayı

# Həll

Bizə verilmiş M x N lövhəsinin sahəsi M\*N, domino parçalarının sahəsi isə 2\*1 yəni 2-dir. Bu o deməkdir ki, lövhədə maksimum lövhənin sahəsi bölünsün domino parçalarının sahəsi qədər domino parçası yerləşdirmək olar.

#### Misal:

M 5-ə, N isə 3-ə bərabərdirsə, maksimum 7 ədəd domino parçası bu lövhədə yerləşdirilə bilər. ( (5\*3)/2 == 7 )

![Solution](../../static/codeforces/800-domino-piling.jpg)

```c
#include "iostream"
using namespace std;
int main()
{
    int M, N;
    cin >> M >> N;
    cout << (M * N) / 2 << endl;
    return 0;
}
```

# Bu şəxslərə minnətdarıq

[Vusal Ismayilov](https://github.com/VusalIs)

<!-- Əgər sualın və ya həllin yaranmasında iştirak etmisinizsə öz github linkinizi bura yaza bilərsiniz -->

<!-- Misal: [Vusal Ismayilov](https://github.com/VusalIs) -->
