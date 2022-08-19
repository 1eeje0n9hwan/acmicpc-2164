import sys
from collcetions import deque
n = int(sys.stdin.readline())
deque = deque([i for i in range(1, n+1)])
while len(deque) > 1:
	deque.popleft()
	data = deque.popleft()
	deque.append(data)
  
print(deque[0])
