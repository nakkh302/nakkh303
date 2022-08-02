java.lang.RuntimeException: It seems that this Microsoft Account does not own the game. Make sure that you have bought/migrated to your Microsoft account.

MSA Error: 404: Not Found, error stream:
{
  "path" : "/minecraft/profile",
  "errorType" : "NOT_FOUND",
  "error" : "NOT_FOUND",
  "errorMessage" : "The server has not found anything matching the request URI",
  "developerMessage" : "The server has not found anything matching the request URI"
}
	at net.kdt.pojavlaunch.authenticator.microsoft.Msa.throwResponseError(Msa.java:293)
	at net.kdt.pojavlaunch.authenticator.microsoft.Msa.checkMcProfile(Msa.java:256)
	at net.kdt.pojavlaunch.authenticator.microsoft.Msa.acquireMinecraftToken(Msa.java:200)
	at net.kdt.pojavlaunch.authenticator.microsoft.Msa.acquireXsts(Msa.java:167)
	at net.kdt.pojavlaunch.authenticator.microsoft.Msa.acquireXBLToken(Msa.java:122)
	at net.kdt.pojavlaunch.authenticator.microsoft.Msa.acquireAccessToken(Msa.java:75)
	at net.kdt.pojavlaunch.authenticator.microsoft.Msa.<init>(Msa.java:35)
	at net.kdt.pojavlaunch.authenticator.microsoft.MicrosoftAuthTask.doInBackground(MicrosoftAuthTask.java:72)
	at net.kdt.pojavlaunch.authenticator.microsoft.MicrosoftAuthTask.doInBackground(MicrosoftAuthTask.java:22)
	at android.os.AsyncTask$3.call(AsyncTask.java:394)
	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:305)
	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1167)
	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:641)
	at java.lang.Thread.run(Thread.java:923)
