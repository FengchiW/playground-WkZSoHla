#include <iostream>

int main() 
{\n
    int N;\n
    std::cin >> N;\n
    for(int i = 0; i < N; i++){\n
        for(int j = 0; j < i; j++)\n
            std::cout << N;\n
        std::cout << std::endl;\n
    }\n
    return 0;\n
}
