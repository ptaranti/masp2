


package scenario.behaviours;

import masp.support.PropertiesLoaderImpl;

public class LoadService {

	public LoadService() {

	}

	public long load(long startTime, long load) {

		long now = System.currentTimeMillis();
		long millis = load * (now - startTime)
				/ ((PropertiesLoaderImpl.EXPERIMENT_DURATION_MIN) * 60000);
		//System.out.println("load: " + millis);
		long a = 0;
		 while (System.currentTimeMillis() < (now + millis)) {
			a++;}

			//System.out.println(System.currentTimeMillis() + "<"
			//		+ (now + millis));
		//	System.out.println(this.toString() + "  " + (System.currentTimeMillis() - now ));
		return System.currentTimeMillis() - now ;
	}
}
