# Unity3D Object Pool

Simple multi prefab supported object pool implementation.
setup. Usage;

	var pool = new ObjectPool(capacity);

instance object

	var instance = pool.instance(prefab);

destroy objects

	pool.destroy(instance );

clear

	pool.clear();

