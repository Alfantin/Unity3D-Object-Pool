# Unity3D Object Pool

Simple multi prefab supported object pool implementation.
setup. Usage;

	var pool = new ObjectPool(capacity);

intance 

	var instance = pool.instance(prefab);
	var instance = pool.instance(prefab, position);
	var instance = pool.instance(prefab, position, rotation);
	
destroy

	pool.destroy(instance);

clear

	pool.clear();

