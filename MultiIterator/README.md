Написать класс  MultiIterator реализующий конкатенацию двух итераторов.
1
2
3
4
5
6
7
8
class MultiIterator<T> implements Iterator<T> {
    private Iterator<T> a;
    private Iterator<T> b;

    public T next();
    public boolean hasNext();
    public void remove();
}
Документация для интерфейса  Iterator есть (https://docs.oracle.com/javase/7/docs/api/java/util/Iterator.html)
