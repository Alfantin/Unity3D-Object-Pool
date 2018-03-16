# Unity3D Object Pool

Simple multi prefab supported object pool implementation.

setup

	var pool = new ObjectPool(capacity);

instance 

	var instance = pool.instance(prefab);
	var instance = pool.instance(prefab, position);
	var instance = pool.instance(prefab, position, rotation);
	
destroy

	pool.destroy(instance);

clear

	pool.clear();

