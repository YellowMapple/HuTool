#Java
```ruby

package IOStreamDay1;

import cn.hutool.core.io.FileUtil;

import java.io.File;
import java.util.ArrayList;

public class Day1 {
    public static void main(String[] args) {
        ArrayList<String> arr = new ArrayList<>();
        arr.add("你好");
        arr.add("hello");
        arr.add("哈喽");
        File gbk = FileUtil.writeLines(arr, "D:\\IDEA\\JAVA-Code\\YellowMaple\\1.txt", "GBK");
        System.out.println(gbk);

    }
}

```
