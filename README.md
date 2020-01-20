# vue-interview

Q1:  v-if 和 v-for  哪个优先级更高？如果两个同时出现，应该怎么优化得到更好的性能？

A: v-for 的优先级更高， 如果同时出现，1、在computed中进行过滤； 2、在数据加载完成之后过滤； 3、在v-for的外层加上v-if。
