# LinearRegression
LinearRegression
import pandas as pd #将函数pandas导入并用pd代替
if __name__ == "__main__":
    data = pd.read_csv("/home/aistudio/data/data4692/simple_example.csv")#括号内容是csv的地址
    print(data["x"],data["y"],data)
