
```JAVA 
/**
 * 네트워크란 컴퓨터 상호 간에 정보를 교환할 수 있도록 연결된 형태를 의미합니다.
 * 예를 들어, 컴퓨터 A와 컴퓨터 B가 직접적으로 연결되어있고, 컴퓨터 B와 컴퓨터 C가 직접적으로
 * 연결되어 있을 때 컴퓨터 A와 컴퓨터 C도 간접적으로 연결되어 정보를 교환할 수 있습니다.
 * 따라서 컴퓨터 A, B, C는 모두 같은 네트워크 상에 있다고 할 수 있습니다.
 *
 * 컴퓨터의 개수 n, 연결에 대한 정보가 담긴 2차원 배열 computers가 매개변수로 주어질 때,
 * 네트워크의 개수를 return 하도록 solution 함수를 작성하시오.
 *
 *
 n	computers	return
 3	[[1, 1, 0], [1, 1, 0], [0, 0, 1]]	2
 3	[[1, 1, 0], [1, 1, 1], [0, 1, 1]]	1

  0  1  2
  1  1  -
  1  1  -
  -  -  1
 */
public class NetworkController {

    public static boolean[] isVisited;

    public static void main(String[] args) {
        int[][] computers = {{1,1,0}, {1,1,0}, {0,0,1}};
        System.out.println(solution(3, computers));
    }

    public static int solution (int n, int[][] computers) {
        int answer = 0;

        isVisited = new boolean[n];
        for (int i = 0; i < n; i++) {
            if(!isVisited[i]) {
                dfs(computers, i);
                answer++;
            }
        }
        return answer;
    }

    public static void dfs (int[][] computers, int i) {
        isVisited[i] = true;

        for (int j = 0; j < computers.length; j++) {
            if (!isVisited[j] && computers[i][j] == 1) {
                dfs(computers, j);
            }
        }
    }
}

```

