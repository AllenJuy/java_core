![image-20200506211033381](/Users/roy/Library/Application Support/typora-user-images/image-20200506211033381.png)

```
Doubly-linked list implementation of the {@code List} and {@code Deque}
interfaces.  Implements all optional list operations, and permits all
elements (including {@code null}).
```

双向链表实现了List 和 Queue的所有接口，实现了list的所有可选操作，和允许的所有元素。

```
* <p>All of the operations perform as could be expected for a doubly-linked
* list.  Operations that index into the list will traverse the list from
* the beginning or the end, whichever is closer to the specified index.
```

所有的执行操作都符合双向链表的预期。操作索引遍历，更接近于指定索引。

```
* <p><strong>Note that this implementation is not synchronized.</strong>
* If multiple threads access a linked list concurrently, and at least
* one of the threads modifies the list structurally, it <i>must</i> be
* synchronized externally.  (A structural modification is any operation
* that adds or deletes one or more elements; merely setting the value of
* an element is not a structural modification.)  This is typically
* accomplished by synchronizing on some object that naturally
* encapsulates the list.
```

**注意这个实现不是同步的，**

如果多个线程同事访问一个链表，并且至少一个线程修改了列表的结构，他必须是外部同步的（结构修改是指添加，删除一个或多个元素的任何操作，仅仅是设置了元素的值不算是结构修改）。这通常是通过对一些自然封装的列表对象同步完成的。