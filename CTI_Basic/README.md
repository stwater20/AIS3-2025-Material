# 威脅實體提取

## 前置安裝

Docker 已安裝

可開啟本機的瀏覽器（如 Chrome）並訪問 http://localhost:8080



## 標註資料

``
docker run -it -p 8080:8080 -v $(pwd)/mydata:/label-studio/data heartexlabs/label-studio:latest
``

### 資料欄位

```
<View>
  <Labels name="label" toName="text">
    <Label value="Idus" background="red"/>
    <Label value="Tool" background="darkorange"/>
    <Label value="HackOrg" background="orange"/>
    <Label value="Area" background="green"/>
  </Labels>

  <Text name="text" value="$text"/>
</View>

```