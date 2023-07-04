Testing the snippet the user provided below:

| 数据集配额 | <p>ZFS 提供快速和准确的数据集、用户和组空间核算，以及配额和空间保留。这使管理员能够精细地控制空间分配，并允许为关键文件系统保留空间。<br>ZFS 支持不同类型的配额：数据集配额、参考<a href="https://docs.freebsd.org/en/books/handbook/zfs/#zfs-term-refquota">配额（refquota）</a>、<a href="https://docs.freebsd.org/en/books/handbook/zfs/#zfs-term-userquota">用户配额</a>和<a href="https://docs.freebsd.org/en/books/handbook/zfs/#zfs-term-groupquota">组配额</a>。<br>配额限制一个数据集及其后代的总大小，包括数据集的快照、子数据集和这些数据集的快照。<br>不能在 ZFS 卷上设置配额，因为 <code>volsize</code> 属性作为一个隐含的配额。</p> |

Trying the same thing with Markdown reference

| 数据集配额 | ZFS 提供快速和准确的数据集、用户和组空间核算，以及配额和空间保留。这使管理员能够精细地控制空间分配，并允许为关键文件系统保留空间
ZFS 支持不同类型的配额：数据集配额、参考[配额（refquota](https://docs.freebsd.org/en/books/handbook/zfs/#zfs-term-refquota)、[用户配额](https://docs.freebsd.org/en/books/handbook/zfs/#zfs-term-userquota)和[组配额](https://docs.freebsd.org/en/books/handbook/zfs/#zfs-term-groupquota)。
配额限制一个数据集及其后代的总大小，包括数据集的快照、子数据集和这些数据集的快照。
不能在 ZFS 卷上设置配额，因为 `volsize` 属性作为一个隐含的配额。|